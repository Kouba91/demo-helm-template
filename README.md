# Demo test for helm library chart
- create new package version  
`helm package ./demolibchart/`
- update `index.yaml`  
`helm repo index docs/ --url https://Kouba91.github.io/demo-helm-template/registry`
