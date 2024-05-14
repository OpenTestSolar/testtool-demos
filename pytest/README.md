## 使用默认配置运行自动化测试

```shell
solarctl apply
```

## 指定测试用例和并发数

```shell
solarctl apply -t "tests/test_assert.py?test_some_primes" -t "tests/test_capitalize.py" --replicas 2
```

## 使用任务模版文件

```shell
solarctl apply -f task_template.yaml
```