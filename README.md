# Check tripleo images parameter used image existed in registry
Run

```
ansible-playbook check_image.yaml -e "image_parameter_path=path-to/container/image/parameter.yaml"
```
Example

```
ansible-playbook check_image.yaml -e "image_parameter_path=~/docker-image-parameter.yaml"
```

