# 인공지능 기반 한국어 비속어 필터링

음소, 음절별로 문장을 분해하여 인공지능을 통해 비속어 여부를 분석 할 수 있습니다.

## Installation

- Use python 3.7

```bash
cd appropriate-filetering
pip install pipenv==2018.10.13 
pipenv install
pipenv run python api.py
```

## Usage
### Website
Just join website (http://host:port)

### API
```http
POST /chk
```

| Parameter | Type | Description |
| :--- | :--- | :--- |
| `text` | `json` | **Required**. 비속어 필터링 할 문장 |

## Responses

욕 or 욕아님