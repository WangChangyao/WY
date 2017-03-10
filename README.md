
样式一：



样式二：



此分页功能在jq.paginator分页插件上稍加修改。

必加模板html：

    <div id="jqPaginator">
        <div id=""></div>
 </div>
　　js:

    $.jqPaginator('#id', {
        totalPages: ,
        visiblePages:,
        pagesize:,
        onPageChange: function (index) {
           //此为回调函数，在点击每个分页按钮时，会自动调用，index会返回当前点击的页码数，可更好在此处与后端进行交互；
           //pagesize可直接用this.pagesize获取
       }
    })
　 

  
