<html><head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="viewport" content="width=device-width">
    <meta charset="utf-8">
    <title>请假外出、返校权限查询通行码</title>
    <style>
        body {
            background: #f2f2f2;
            margin: 0;
            padding: 0;
            font-family: "Microsoft YaHei";
            color: #333;
        }

        #main {
            display: flex;
            width: 100vw;
            flex-direction: column;
            position: absolute;
            background: #f2f2f2;
            min-height: 100vh;
        }

        #menu {
            background: white;
            display: inline-block;
            height: 50px;
            line-height: 50px;
            color: #878787;
            font-size: 16px;
            background: #fff;
            position: relative;
            border-bottom: .01rem solid #ececec;
            padding-left: 5px;
            z-index: 2;
        }


        #menu span {
            display: inline-block;
            border-bottom: 3px solid #4285f4;
            height: 100%;
            box-sizing: border-box;
            width: 150px;
            text-align: center;
        }

        #button {
            margin: 10px;
            background: white;
            padding: 16px;
            font-size: 12px;
            font-family: PingFang SC;
            font-weight: bold;
            color: #333;
        }

        #button img {
            height: 1.25em;
            width: 1.25em;
            line-height: 100%;
            vertical-align: middle;
            margin-right: 5px;
        }

        .title {
            color: rgb(135, 135, 135);
            font-size: 14px;
            font-family: 微软雅黑;
            padding: 8px;
            padding-left: 16px;
        }

        .value {
            font-size: 14px;
            color: rgb(96, 98, 102);
            text-decoration: none;
            text-align: center;
            /* line-height: 50px; */
            background: white;
            padding: 16px;
        }


        #title-status {
            font-size: 18px;
        }

        #status {
            color: rgb(57, 132, 41);
            font-weight: bold;
            font-size: 18px;
        }

        #hint {
            height: 50px;
            text-align: center;
            color: rgb(135, 135, 135);
            font-size: 14px;
            position: absolute;
            width: 100%;
            margin-top: 20px;
        }

        #more {
            position: fixed;
            bottom: 0;
            height: 50px;
            background: white;
            width: 100%;
            padding-left: 20px;
        }

        #more button {
            outline: none;
            border: 1px solid #4285f4;
            background: unset;
            border-radius: 20px;
            font-size: 18px;
            padding: 5px 20px;
            display: inline-block;
            margin: 10px;
            color: #4285f4;
            cursor: pointer;
        }

        #footer {
            position: fixed;
            bottom: 0;
            height: 120px;
            width: 100%;
        }

        #footer p {
            background: white;
            padding: 10px;
            text-align: center;
            color: #4285f4;
            cursor: pointer;
        }

        #modal {
            position: absolute;
            z-index: 3;
        }

        #modal .modal-body {
            background: white;
            width: 700px;
            height: 500px;
            padding: 20px;

        }

        #modal table {
            margin: 20px;
            border: 1px solid;
        }

        #modal td {
            text-align: center;
            padding: 10px;
        }

        #modal .modal-close {
            width: 1em;
            background: white;
            display: inline-block;
            height: 1em;
            padding: 5px;
            border-radius: 100%;
            text-align: center;
            vertical-align: top;
            top: 0;
            line-height: 100%;
            font-weight: bold;
            margin: 20px;
        }
    </style>
    
</head>

<body>
    <div id="hint">网页由 service.bupt.edu.cn 提供</div>
    <div id="main">
        
        <div id="button"><img src="title.png">当前部门：理学院
            <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACoAAAAYCAYAAACMcW/9AAAB4ElEQVRYR83VO0sDQRAA4Nm9LfMbBBEsBC1EEFGUJblcOEihP8Je8YnYiPhErf0Rlja729j4C6wUE1+o+AAtlMiaHTmJcsYkbi6R3FVX7Mx+Nzs7RwAAhBCCEOIG73F8KKU+UUqNI+JuHIEh03UAPUDE4ZhD34mUcg8AxmIPVUoNIOJhzKH7JABKKScAYDuOWES8SiQSnZ/QEnYaADZihj1mjI1wzm+/oaUxtUQIWYwJNo+IQ+l0+jrw/ICWKrsAAMstxt5prdt833/7cvyCthpLCDlzHGcgOO5wsSpCW4g9oZS6yWTyvPxEq0JbgL0wxnR5nvdSqe1qQoMApdQMIq7/c8/eaK3bwz1ZV0W/Fiul5hFx5Z+wuWKxOJTJZG5q5f+zoqE5OwcAq03G5hhjg+UXJ9LRh4Oa3Aa3hUKhI5vNvtp8vHVFm9wGl4yxXs75gw2y4sC3CWywsnmtdb/v+/c2e9Uc+DYJlFKTiLhlsza05hIAul3Xfa4z7vcvtJ4EQohZQsiaTUzwxwGAvlQq9WizPtJ4qpXYEpsv9eRTFGTkHi3fTEo5BQCbVRAXANAT5bjD+eq+9dUqUgV7ZIxJep53F7WSDV+mShsLIUYppSPGmASl9NRxnB3OeaFRZBD/ATVSvUcGtzefAAAAAElFTkSuQmCC" alt="" style="float: right;width: 9px;height: 5px;margin-top: 10px;"></div>

        <div id="button" style="margin-top:-3px;"><img src="data:image/png;base64,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">请假外出、返校权限查询
        </div>
        <div id="title-name" class="title">姓名</div>
        <div id="name" class="value">
	        田悦含
	</div>
	 <div id="title-college" class="title">照片</div>
         
        <div id="code" class="value">
<!--		<select id = "picId" onclick = "change()">
			<option>lwr</option>
			<option>xyy</option>
		</select> -->
		<img id="picurl" src="tyhpic.jpg" style="width:115px;height:330px;border-radius:5px;">
        </div>
	<script>
		function change(){
			var pic = document.getElementById("picId").value;
			console.log(pic);
			var p = document.getElementById("picurl");
			p.style.display = block;
		}
	</script>
        <div id="title-code" class="title" style="margin-top:-3px;"> </div>
        <div id="college" class="value"><img src="switch.gif" style="width: 370px; height: 35px;"></div>
        <div id="title-code" class="title">状态码</div>
        
        
        <div id="code" class="value"><img src="green.png" style="width:166.5px;height:166.5px;">
        </div>
        <div id="status" class="value" style="margin-top:10px;">允许入校</div>
        <div id="title-id" class="title">学工号</div>
        <div id="id" class="value">2021110482</div>
        <div id="title-time" class="title">出入校时间</div>
        <div id="time" class="value">2021-10-29 19:31:02</div>
	<div id="title-college" class="title">学院</div>
        <div id="college" class="value">电子工程学院</div>

	<div style="height:100px"></div>
    </div>

    <div id="more">
        <button onclick="javascript:clickMore()">更多</button>
    </div>

    <div id="footer" style="display:none">
        <p onclick="javascript:clickModal()">预览表单</p>
        <p onclick="javascript:clickCancel()">取消</p>
    </div>

 
    <script>

        function clickMore() {
            var main = document.getElementById("main")
            var more = document.getElementById("more");
            var footer = document.getElementById("footer");
            var modal = document.getElementById("modal");
            main.style.filter = "brightness(0.5)";
            main.onclick = clickCancel;
            more.style.display = "none";
            footer.style.display = "";
            modal.style.display = "none";
        }

        function clickCancel() {
            var main = document.getElementById("main")
            var more = document.getElementById("more");
            var footer = document.getElementById("footer");
            var modal = document.getElementById("modal");
            main.style.filter = "";
            main.onclick = undefined;
            more.style.display = "";
            footer.style.display = "none";
            modal.style.display = "none";
        }

        function clickModal() {
            var main = document.getElementById("main")
            var more = document.getElementById("more");
            var footer = document.getElementById("footer");
            var modal = document.getElementById("modal");
            main.style.filter = "brightness(0.5)";
            main.onclick = clickCancel;
            more.style.display = "none";
            footer.style.display = "none";
            modal.style.display = "";
        }

        function getQueryVariable(variable) {
            var query = window.location.search.substring(1);
            var vars = query.split("&");
            for (var i = 0; i < vars.length; i++) {
                var pair = vars[i].split("=");
                if (pair[0] == variable) { return decodeURI(pair[1]); }
            }
            return (false);
        }

        window.onload = function () {
            var time = document.getElementById("time");
            var timeTD = document.getElementById("time2");
            var date = new Date();
            time.innerText = `${date.getFullYear()}-${(date.getMonth() + 1).toString().padStart(2, 0)}-${(date.getDate()).toString().padStart(2, 0)} ${(date.getHours()).toString().padStart(2, 0)}:${(date.getMinutes()).toString().padStart(2, 0)}:${(date.getSeconds()).toString().padStart(2, 0)}`;
            timeTD.innerText = time.innerText;

            var keys = ["name", "college", "status", "id"]
            keys.map(function (key) {
                var data = getQueryVariable(key)
                if (!!data) {
                    try {
                        var div = document.getElementById(key);
                        div.innerText = data;
                    } catch{ }
                    try {
                        var td = document.getElementById(`${key}2`);
                        td.innerText = data;
                    }
                    catch{ }

                }
            })

            var app = document.getElementById("main");
            var touchstartY;
            app.addEventListener("touchstart", function (event) {
                var events = event.touches[0] || event;
                touchstartY = events.clientY;//获取触摸目标在视口中的y坐标
            }, false);

            app.addEventListener("touchmove", function (event) {
                var events = event.touches[0] || event;
                //注意document.body.scrollTop始终为0
                var scrollTop = document.body.scrollTop || document.documentElement.scrollTop;//获取滚动部分的高度
                var clientHeight = document.documentElement.clientHeight;//获取手机屏幕高度（可视部分高度）
                var scrollHeight = document.body.scrollHeight;//所有内容的高度
                if (events.clientY > touchstartY && scrollTop === 0 && event.cancelable) {
                    // console.log(events.clientY, touchstartY)
                    app.style.top = Math.sqrt(Math.pow(events.clientY - touchstartY, 1.5));
                    event.preventDefault();//禁止到顶下拉
                }
            }, false);

            app.addEventListener("touchend", function (event) {
                app.style.transition = 'top 0.25s';
                app.style.top = 0;
                setTimeout(() => {
                    app.style.transition = '';
                }, 500);
            }, false);
		//document.write("请按照规定使用官方途径申请绿码出入校");
        }

    </script>



</body></html>
