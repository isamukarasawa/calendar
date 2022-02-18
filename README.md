

## calendar_テーブル

| Column             | Type       | Options    |
| ------------------ | ---------- | ---------- |
| todo               | string     |            |
| memo               | string     |            |
| diary              | string     |            |
| start-time         | string     | null: false|


### Association
- has_many :items
- has_many :orders

## word_テーブル

| Column               | Type        | Options                        |
| -------------------- | ----------- | ------------------------------ |
| word                 | string      | null: false                    |

