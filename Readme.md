## Helm 3

- Repositório para armazenamento de templates helm

![](./img/helm.jpg)

## Estrutura

```console

- repo
    - templates
        - base-templates
            - templates
            - .helmignore
            - Chart.yaml
            - values.yaml

        - dotnet
            - project1
                - templates
                - .helmignore
                - Chart.yaml
                - values.yaml
                
        - java
            - project1
                - templates
                - .helmignore
                - Chart.yaml
                - values.yaml

```