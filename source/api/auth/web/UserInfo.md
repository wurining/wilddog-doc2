
title: UserInfo
---

User 对象包含所有维护用户个人信息的接口，我们不能直接创建此对象，只能通过 `wilddog.auth().currrentUser` 或者部分登录接口来获取 User 的实例。

## 属性

### displayName

**定义**

```js
nullable string
```

**说明**

用户名称

</br>

------

### email

**定义**

```js
nullable string
```

**说明**

用户主邮箱地址

</br>

------

### photoURL

**定义**

```js
nullable string
```

**说明**

用户照片地址

</br>

------

### providerId

**定义**

```js
string
```

**说明**

当前用户登录使用的身份认证提供商名称，例如weibo，weixin。

</br>

------

### uid

**定义**

```js
string
```

**说明**

Wilddog Id

</br>