


<pre>
    <code>
        ajaxJsonp({
            url:'https://api.map.baidu.com/location/ip',
            time:100000,
            data:{ak:''},
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