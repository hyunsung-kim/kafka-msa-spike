# kafka-msa-spike
Kafka를 사용하는 방법은 Confluent와 kafka-python 두가지가 있다. <br/>
Confluent 라이브러리는 C로 작성되었지만 속도 측면에서는 더 빠른다. <br/>
반면 kafka-python은 Confluent 라이브러리에 비하여 느리지만, 간편하게 사용할 수 있는 장점이 있다.

## Getting Started
여기서는 카프라의 kafka-python을 간단한 사용방식을 알아보도록 하겠다.

### Kafka
```
$ cd kafka
$ docker-compose up
```

### Producer

```bash
$ pipenv run python producer.py
```

### Consumer

```bash
$ pipenv run python consumer.py
```

## Reference
- [kafka docker](https://www.joinc.co.kr/w/man/12/Kafka/docker)
- [kafka-python](https://needjarvis.tistory.com/607)
