[TOC]

### discovery_list

#### 数据请求

* store.js 

```json
	discovery_data_list_all: [], 列表数据存储
	discovery_data_list_all_other: {},总条数数据存储
```

* action.js

  ​

| function                       | params          | 是否必须 | 参数说明                  | 方法说明                            |
| ------------------------------ | --------------- | ---- | --------------------- | ------------------------------- |
| discovery_data_list            | if_request_data | N    | true 主动强制请求数据         |                                 |
| discovery_data_list_update     |                 |      |                       | 刷新所有的发现列表4个                     |
| discover_data_list_item_delete | item_id         | Y    | witch you will del it | del discovery item from  server |
|                                |                 |      |                       |                                 |





### brands_list 

#### 数据请求

- store.js 

```json
	brands_data_list: [], 列表数据存储
	brands_data_list_other: {},总条数数据存储
```

- action.js

  ​

| function         | params          | 是否必须 | params desc   | function desc |
| ---------------- | --------------- | ---- | ------------- | ------------- |
| brands_data_list | if_request_data | 否    | true 主动强制请求数据 |               |
|                  |                 |      |               |               |







### store_list 

#### 数据请求

- store.js 

```json
	store_data_list: [], 列表数据存储
	store_data_list_other: {},总条数数据存储
```

- action.js

  ​

| function        | params          | 是否必须 | params desc   | function desc |
| --------------- | --------------- | ---- | ------------- | ------------- |
| store_data_list | if_request_data | 否    | true 主动强制请求数据 |               |
|                 |                 |      |               |               |





### five_floor_data_list

#### 数据请求

- store.js 

```json
	store_data_list: [], 列表数据存储
	store_data_list_other: {},总条数数据存储
```

- action.js

  ​

| function             | params          | 是否必须 | params desc   | function desc |
| -------------------- | --------------- | ---- | ------------- | ------------- |
| five_floor_data_list | if_request_data | 否    | true 主动强制请求数据 |               |
|                      |                 |      |               |               |



