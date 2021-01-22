# @domain.js/redis

[![Build status](https://travis-ci.com/domain-js/redis.svg?branch=master)](https://travis-ci.org/domain-js/redis)
[![codecov](https://codecov.io/gh/domain-js/redis/branch/master/graph/badge.svg)](https://codecov.io/gh/domain-js/redis)

# Installation
<pre>npm i @domain.js/redis --save</pre>

# cnf
专属配置名称 `redis`
| 名称 | 类型 | 必填 | 默认值 | 描述 | 样例 |
| ---- | ---- | ---- | ------ | ---- | ---- |
| host | string | `是` | `无` | redis 地址 | 127.0.0.1 |
| port | string|number | `是` | `无` | redis 端口 | 6379 |
| keyPrefix | string | `是` | `无` | redis 前缀，为了隔离不同应用的数据 | RED:: |

# deps
<pre>无</pre>


# Usage
[功能用法参考 ioredis](https://github.com/luin/ioredis)
