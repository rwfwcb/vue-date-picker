# date-picker-vue2

> datepicker component for Vue.js.

# screenshot

![screenshot](screenshot.png)

# Requirements

- [Vue.js](https://github.com/yyx990803/vue) `^2.0.0`
- [Bootstrap](https://github.com/twbs/bootstrap) `>=3.0`

# Installation

## npm 
``` bash
$ npm install date-picker-vue2
```

# Usage
``` html
<template>
    <datepicker :readonly="true" format="YYYY-MM-DD"></datepicker>
    <datepicker format="YYYY-M-D" v-model="date"></datepicker>
    <datepicker :readonly="true" format="MM/DD/YYYY" width="300px"></datepicker>
    <datepicker :readonly="true" format="MM/DD/YYYY" width="300px" name="date"></datepicker>
    <datepicker width="inherit" color="#f48024" hoverColor="#e67e00" v-model="date"></datepicker>
</template>

<script>
import datepicker from 'date-picker-vue2';

export default {
    components: { datepicker }
};
</script>
```

# License

[The MIT License](http://opensource.org/licenses/MIT)
