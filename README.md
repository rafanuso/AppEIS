### Caçakids
O projeto Caçakids é um divertido jogo infantil onde se aprende o nome dos objetos de forma lúdica, com ilustrações para facilitar o apredizado.
Na primeira tela é a apresentação do logo e nome do App. Na segunda tela o usuário vai fazer o cadastro e posteriormente login. Apartir da 3 tela o usuário ja começa sua jornada rumo ao aprendizado.

Estrutura de Diretórios
caçakids_project/│
├── main.py             # Código principal do app
├── screens/            # Diretório com as telas do app│   
├── logo_screen.py      # Tela de apresentação│   
├── login_screen.py     # Tela de login/cadastro│   
└── learning_screen.py  # Tela de aprendizado
├── kv_files/           # Diretório para arquivos de layout .kv│   
├── logo_screen.kv│   
├── login_screen.kv│   
└── learning_screen.kv
├── assets/             # Imagens e outros recursos│   
├── logo.png│   
└── illustrations/      # Ilustrações para a tela de aprendizado
└── utils/              # Código auxiliar (ex.: validação, banco de dados)
    └── database.py     # Lógica para armazenamento de dados

