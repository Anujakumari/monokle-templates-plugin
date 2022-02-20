# Monokle
Monokle is a friendly desktop UI for creating, validating, debugging and managing Kubernetes manifests.

## Monokle helps you to:

- quickly get a high-level view of your manifests and their contained resources <br>
- easily edit resources without having to learn yaml syntax, <br>
- diff resources against your cluster, <br>
- preview and debug resources generated with kustomize or Helm, and more. <br>
- It also allows your team to avoid drifts between your manifests and clusters as you keep adding more and more components. <br>

[Monokle documentation](https://kubeshop.github.io/monokle/)

## Monokle Template
A Monokle Template is a mechanism for creating visual forms and interpolating the data from those forms into one or multiple manifests.
For each form, we must define the JSON schema of the data to use as an input and a UI-schema for customizing the visuals of the forms. <br>

[Templates documentation](https://kubeshop.github.io/monokle/templates/)

## Plugin 
Simply, any GitHub repository that contains a package.json file (the plugin entry file) can be installed as a plugin if the entry file follows the structure of a Monokle plugin.

[Plugins documentation](https://kubeshop.github.io/monokle/plugins/)

## How to Create a YAML Manifest Template in Monokle
[Blog URL](https://anuja-kumari.medium.com/create-a-yaml-manifest-template-in-monokle-617e112f6772)
