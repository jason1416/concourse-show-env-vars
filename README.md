# concourse-show-env-vars
#### push to concourse
```
fly -t aws sp -p showenv -c pipeline.yml

env vars have to be passs in as params: in pipeline.yml

```


##### check the env vars 
```
fly -t aws tj -j showenv/run -w
```

