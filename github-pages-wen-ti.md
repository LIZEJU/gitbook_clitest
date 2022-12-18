# github pages问题

## github personal access token 失效

```
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
```

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption><p>token失效</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption><p>重新激活token</p></figcaption></figure>

```
关于 personal access token
使用 GitHub API 或命令行时，可使用 Personal access 
token 替代密码向 GitHub 进行身份验证。 Personal access
 token 旨在代表你自己访问 GitHub 资源。 若要代表组织访问
 资源，或为长时间的集成而访问，应使用 GitHub App。 有关详细信息
 ，请参阅“关于应用”。


GitHub 目前支持两种类型的 personal access token：
fine-grained personal access token 和 personal 
access tokens (classic)。 GitHub 建议尽可能使用 
fine-grained personal access token 而不是 
personal access tokens (classic)。 与 
personal access tokens (classic) 相比，
Fine-grained personal access token 具有几个安全优势：

每个令牌只能访问单个用户或组织拥有的资源。
每个令牌只能访问特定的存储库。
每个令牌都被授予特定的权限，这些权限比授予 personal access tokens (classic) 的范围提供更多的控制。
每个令牌都必须具有到期日期。
组织所有者可要求必须获取对可访问组织中资源的任何 fine-grained personal access token 的批准。

https://docs.github.com/zh/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token


github access token 过期
```

过期时间最好设置为7天，我设置的很长的过期时间，不知道什么情况，一会就过期了

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>
