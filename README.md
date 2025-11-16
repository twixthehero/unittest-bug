# unittest-bug

This repo reproduces a bug with the Helm unittest plugin.

## How to reproduce

```shell
$ helm plugin install https://github.com/helm-unittest/helm-unittest.git --version 1.0.3
$ helm unittest my-chart
$ helm unittest my-second-chart
```

## Version info

```shell
$ helm version          
version.BuildInfo{Version:"v3.19.2", GitCommit:"8766e718a0119851f10ddbe4577593a45fadf544", GitTreeState:"clean", GoVersion:"go1.24.9"}

$ helm plugin list
NAME    	VERSION	DESCRIPTION                                                                         
unittest	1.0.3  	Unit test for helm chart in YAML with ease to keep your chart functional and robust.
```
