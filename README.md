# runtime-github-action-deploy

[![Action test Ubuntu](https://github.com/stack-spot/runtime-github-action-ping/actions/workflows/action-test-ubuntu.yaml/badge.svg)](https://github.com/stack-spot/runtime-github-action-ping/actions/workflows/action-test-ubuntu.yaml)

GitHub action to run StackSpot Runtime Deploy Worker.

_**Note**: This action is supported on debian/RHEl like systems

## 📚 Usage

### Requirements

### Use Case

```yaml
    steps:
      uses: stack-spot/runtime-github-action-deploy@v1
      with:
        FEATURES_LEVEL_LOG: debug
        INPUT_PATH: deploy.yaml

```

## License

[Apache License 2.0](https://github.com/stack-spot/runtime-github-action-deploy/blob/main/LICENSE)