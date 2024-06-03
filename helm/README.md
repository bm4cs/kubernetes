# helm

Based on the official [Chart Template Guide](https://helm.sh/docs/chart_template_guide/)

- [YAML techniques](https://helm.sh/docs/chart_template_guide/yaml_techniques/)
- [Built-in Objects](https://helm.sh/docs/chart_template_guide/builtin_objects/)
- 

```sh
helm install full-coral ./mychart
helm get manifest full-coral    # see raw template result
helm uninstall full-coral
helm install --debug --dry-run goodly-guppy ./mychart   # test render without installing
```

Continue at <https://helm.sh/docs/chart_template_guide/builtin_objects/>