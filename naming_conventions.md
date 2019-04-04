# 変数命名規約
## Prefix
1文字目 スコープ
2文字目 変数型
3文字目 _

### スコープ
| スコープ | Prefix |
----|---- 
| ローカル | L |
| グローバル | G |
| インスタンス | M |
| クラス | S |
| Importing | I |
| Exporting | E |
| Changing | C |
| Returning | R |

### 変数型
| 変数型 | Prefix |
----|---- 
| 変数 | V |
| 定数 | C |
| 構造 | S |
| 内部テーブル | T |
| データ参照 | R |
| オブジェクト参照 | O |

### 例
メソッド内で定義するローカル変数

`DATA lv_hoge TYPE i.`
