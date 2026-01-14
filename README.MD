# Home Assistant Config Files

## Sobre

Este é meu conjunto de arquivos de configuração da plataforma Home Assistant baseada no [Config Files de Franck Nijhof](https://github.com/frenck/home-assistant-config)

O setup começa em configuration.yaml que lê todas as configurações de integrações da pasta /integrations

## Integrações Notáveis
### Automações, Cenas e Scripts

Estas integrações carrregam 2 tipos de configurações:

1) Um conjunto de configurações customizadas e editáveis somente em formato yaml localizadas em custom_automations, custom_scenes e custom_scripts respectivamente 

    > Exemplo usando a integração scene
    > - /custom_scenes
    >     - scene01.yaml    
    >     - scene02.yaml
    >     - /group03
    >         - group03-scene01.yaml

2) Um arquivo de configuração, que pode ser editada via interface localizadas em automations.yaml, scenes.yaml e scripts.yaml respectivamente

    > Exemplo usando a integração scene
    > - scenes.yaml

### Frontend

Esta integração carrega temas personalizados configurados dentro de [./custom_themes](./custom_themes)