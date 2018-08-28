


<pre>
    <code>
        ajaxJsonp({
            url:'https://api.map.baidu.com/location/ip',
            time:100000,
            data:{ak:'t3vLgtin6N7rfKU2oedXfWwlQoB5iFlf'},
            jsonp:'ajaxJsonplocation',
            error:function () {
            },
            success:function (info) {
                console.log(info)
                window.userPositionInfo=info.content
            },

        })
    </code>
</pre>