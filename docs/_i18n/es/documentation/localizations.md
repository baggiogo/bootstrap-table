# Localizations []({{ site.repo }}/blob/develop/docs/_i18n/{{ site.lang }}/documentation/localizations.md)

---

<table class="table"
       id="l"
       data-search="true"
       data-show-toggle="true"
       data-show-columns="true"
       data-mobile-responsive="true">
    <thead>
    <tr>
        <th>Nombre</th>
        <th>Parámetro</th>
        <th>Valor por defecto</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>formatLoadingMessage</td>
        <td>-</td>
        <td>'Loading, please wait…'</td>
    </tr>
    <tr>
        <td>formatRecordsPerPage</td>
        <td>pageNumber</td>
        <td>'%s records per page'</td>
    </tr>
    <tr>
        <td>formatShowingRows</td>
        <td>pageFrom, pageTo, totalRows</td>
        <td>'Showing %s to %s of %s rows'</td>
    </tr>
    <tr>
        <td>formatDetailPagination</td>
        <td>totalRows</td>
        <td>'Showing %s rows'</td>
    </tr>
    <tr>
        <td>formatSearch</td>
        <td>-</td>
        <td>'Search'</td>
    </tr>
    <tr>
        <td>formatNoMatches</td>
        <td>-</td>
        <td>'No matching records found'</td>
    </tr>
    <tr>
        <td>formatRefresh</td>
        <td>-</td>
        <td>'Refresh'</td>
    </tr>
    <tr>
        <td>formatToggle</td>
        <td>-</td>
        <td>'Toggle'</td>
    </tr>
    <tr>
        <td>formatColumns</td>
        <td>-</td>
        <td>'Columns'</td>
    </tr>
	<tr>
        <td>formatAllRows</td>
        <td>--/td>
        <td>'All'</td>
    </tr>
    <tr>
        <td>formatFullscreen</td>
        <td>-</td>
        <td>'Fullscreen'</td>
    </tr>
    </tbody>
</table>

---

**PS:**

Podemos importar  [all locale files](https://github.com/wenzhixin/bootstrap-table/tree/master/src/locale) lo que necesita:

```html
<script src="bootstrap-table-en-US.js"></script>
<script src="bootstrap-table-zh-CN.js"></script>
...
```

Y luego utilice este código JavaScript para cambiar el lenguaje:

```js
$.extend($.fn.bootstrapTable.defaults, $.fn.bootstrapTable.locales['en-US']);
// $.extend($.fn.bootstrapTable.defaults, $.fn.bootstrapTable.locales['zh-CN']);
// ...
```

O utilice los data attributes para configurar el lenguaje:

```html
<table data-toggle="table" data-locale="en-US">
</table>
```

O utilice este JavaScript para configurar el lenguaje:

```js
$('table').bootstrapTable({locale:'en-US'});
```
