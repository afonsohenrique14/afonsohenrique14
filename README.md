
perfil_dev = {
    "nome": "Afonso Henrique Guimarães de Oliveira",
    "titulo": "Desenvolvedor | Automação & Eficiência",
    "bio": "Olá! Sou um desenvolvedor apaixonado por automação, deploy inteligente e versionamento eficiente. Com experiência em desenvolvimento de sistemas departamentais na Caixa Econômica Federal, busco sempre otimizar processos e criar soluções escaláveis.",
    "tecnologias_habilidades": {
        "linguagens": ["Python", "JavaScript", "SQL", "VBA", "HTML", "CSS"],
        "banco_de_dados": ["MySQL", "PostgreSQL"],
        "versionamento": ["Git", "GitHub Actions"],
        "deploy_ci_cd": "Automação de publicações e gerenciamento de versões",
        "aprendizado_continuo": "Atualmente explorando Docker para otimizar implantação e escalabilidade de aplicações."
    },
    "formacao_academica": [
        {"grau": "Bacharelado", "curso": "Ciências Contábeis", "instituicao": "Universidade Federal do Tocantins (UFT)"},
        {"grau": "Pós-Graduação", "curso": "Contabilidade Pública", "instituicao": "Faculdade Unyleya"},
        {"grau": "Tecnólogo", "curso": "Análise e Desenvolvimento de Sistemas", "instituicao": "UNIFAVIP Wyden"}
    ],
    "onde_me_encontrar": {
        "linkedin": "[linkedin.com/in/seu-perfil](https://www.linkedin.com/in/afonso-henrique-guimarães-oliveira-84000431)",
        "github": "[github.com/seu-usuario](https://github.com/afonsohenrique14)"
    },
    "projetos_destaque": [
        "Automação de deploys com GitHub Actions 🚀",
        "Sistemas financeiros e departamentais 📊",
        "Explorando Docker para automação e escalabilidade 🐳",
        "Contribuindo para um mundo mais automatizado, eficiente e organizado!  "
    ]
}

# Para imprimir o dicionário completo
print(perfil_dev)

# Para acessar informações específicas
print(f"Nome: {perfil_dev['nome']}")
print(f"Linguagens: {', '.join(perfil_dev['tecnologias_habilidades']['linguagens'])}")
print(f"GitHub: {perfil_dev['onde_me_encontrar']['github']}")
