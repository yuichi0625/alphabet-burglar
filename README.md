# alphabet-thief

## Requirements


## Installation
```
pip install alphabet_thief
```

## Usage
```python
import alphabet_thief

text = 'Hello, how are you?'
result = alphabet_thief.steal(text)
print(f'result: "{}"')
```

```
result: "     ,            ?"
```

```python
text = 'Hello, how are you?'
result = alphabet_thief.replace(text, 'a')
print(f'result: "{}"')
```

```
result: "aaaaa, aaa aaa aaa?"
```

```python
text = 'Trời mưa thì phải ở nhà.'
result = alphabet_thief.steal(text)
print(f'result: "{}"')
```

```
result: "   ̛̀    ̛     ̀    ̉   ̛̉    ̀."
```

```python
text = 'Trời mưa thì phải ở nhà.'
result = alphabet_thief.replace(text, 'a')
print(f'result: "{}"')
```

```
result: "aaà̛a aa̛a aaà aaảa ả̛ aaà."
```
