## add helm repo
helm3 repo add stevehipwell https://stevehipwell.github.io/helm-charts/

## helm install plantuml for gitlab
helm3 install -n plantuml --values ./plantuml2gitlab.yaml plantuml stevehipwell/plantuml

## helm install plantuml on 111 for gitlab
helm3 install -n plantuml-111 --values ./plantuml2gitlab-111.yaml plantuml-111 stevehipwell/plantuml
