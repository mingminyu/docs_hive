# 其他函数


## 1. HASH

## 2. MD5

## 3. CRC32

## 4. SHA2

Hive SHA2 函数支持对字段进行 SHA224、SHA256、SHA384 以及 SHA512 算法加密。

```sql linenums="1"
SELECT sha2('ABC', 0);  -- 表示不做加密

SELECT sha2('ABC', 224);

SELECT sha2('ABC', 256);

SELECT sha2('ABC', 384);

SELECT sha2('ABC', 512);
```


## 5. AES_ENCRYPT


## 6. AES_DECRYPT


## 7. XPATH

## 8. GET_JSON_OBJECT


