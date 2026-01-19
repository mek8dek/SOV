# SOV
Jogo de estrategia geopolitica e soberania economica 
SOV/
├── README.md
├── project.godot
├── Menu.tscn
├── Menu.gd
├── Game.tscn
├── Game.gd
└── assets/
    └── logo.png
    # SOV — Sovereignty

SOV é um jogo de estratégia geopolítica e econômica onde o jogador controla
a soberania de uma nação por meio de decisões financeiras, dívida pública
e poder político.

## 🎮 Conceito
- Controle de países
- Emissão de títulos soberanos
- Gestão de dívida e reservas
- Crises econômicas e crescimento
- Soberania (SOV) como métrica central

## 🛠️ Tecnologia
- Engine: Godot
- Linguagem: GDScript
- Plataforma: PC / Mobile

## 🚀 Status
Em desenvolvimento — menu jogável inicial.

## 📌 Próximos passos
- Seleção de país
- Tela principal com mapa
- Sistema de turnos
- Economia dinâmica

---
extends Control

func _on_novo_jogo_pressed():
    get_tree().change_scene_to_file("res://Game.tscn")

func _on_sair_pressed():
    get_tree().quit()
    extends Control

func _ready():
    print("SOV iniciado")
    
