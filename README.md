# 农历公历整合插件（jQuery）


## 用法

``` html
<div class="solar-lunar-date">
  <select id="date-type" name="useLunar" class="solar-lunar-date-type">
    <option value="false">公历</option>
    <option value="true">农历</option>
  </select>
  <input type="hidden" class="lunar-date-value" name="lunar-date-value"/>
  <select class="lunar-year"></select>
  <select class="lunar-month"></select>
  <select class="lunar-date"></select>
  <input type="text" class="solar-date-picker" name="dob"/>
</div>
```

``` javascript
$('#date-type').solarLunarDate({
  lunarField: '.lunar-date-value',
  solarField: '.solar-date-picker',
  minDate: new Date(1900,1,1),
  maxDate: new Date()
});
```
