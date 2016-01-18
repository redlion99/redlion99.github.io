---
layout: home
---

<div class="index-content project">
    <div class="section">
        <ul class="artical-cate">
            <li><a href="/"><span>Blog</span></a></li>
            <li style="text-align:center"><a href="/opinion"><span>Opinion</span></a></li>
            <li class="on" style="text-align:right"><a href="/project"><span>Project</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.project %}
            <li>
                <h2>
                    <a href="{{ post.url }}">{{ post.title }}</a>
                </h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
        <form id="clForm" data-cl-attached="true" data-cl-id="0cb9910a71f540f791d686a021fe2e3d" action="http://host.51convert.cn/page/0cb9910a71f540f791d686a021fe2e3d" method="POST"></form>
        <script type="text/javascript" src="http://host.51convert.cn/js/forms/form.js"></script>
        <script>
        	_clForm.loadForm("http://host.51convert.cn", "0cb9910a71f540f791d686a021fe2e3d",{
        		formInit: function(){},
        		beforeSubmit: function(){},
        		onSubmit: function(args){}
        	});
        </script>
    </div>
    <div class="aside">
    </div>
</div>
