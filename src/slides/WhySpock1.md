## Why Spock?

```groovy
class MyFirstSpec extends Specification {
  def "let's try this!"() {
    expect:
    Math.max(1, 2) == 3
  }
}
```
