## add helm repo
helm3 repo add stevehipwell https://stevehipwell.github.io/helm-charts/

## helm install plantuml for gitlab
helm3 install -n plantuml --values ./plantuml2gitlab.yaml plantuml stevehipwell/plantuml