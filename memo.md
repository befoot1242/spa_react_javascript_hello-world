# react と spring を共存させたいが。。。

`Application Authentication: none`\
を指定しないと、react 側で認証がうまくいかなかった。

ただ、それをすると
`Grant Types: Client Credentials`\
が効かなくなるので、Sprint に対してトークンでのリクエストが通らない
