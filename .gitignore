<!DOCTYPE HTML>
<html class="small-scroll-bar no-js bg" lang="zh-cmn-Hans">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1"/>
    <meta charset="UTF-8">
    <!--IE 8浏览器的页面渲染方式-->
    <meta http-equiv="X-UA-Compatible" content="IE=edge, chrome=1">
    <!--默认使用极速内核：针对国内浏览器产商-->
    <meta name="renderer" content="webkit">
    <!--chrome Android 地址栏颜色-->
    <meta name="theme-color" content="#3a3f51"/>
<!--    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">-->
<!--    <meta name="mobile-web-app-capable" content="yes">-->
<!--    <meta name="apple-mobile-web-app-capable" content="yes">-->
<!--    <meta name="apple-mobile-web-app-status-bar-style" content="default">-->
    <meta http-equiv="x-dns-prefetch-control" content="on">

    <title>腾讯云对象存储 COSCMD 工具安装配置与使用命令  - 思有云 - IOIOX</title>
            <link rel="icon" type="image/ico" href="/favicon.ico">
        <meta name="description" content="前言COSCMD 工具是一款腾讯云 COS 的命令行操作工具,能方便的在 Linux 服务器上管理对象存储 COS 中的桶文件,支持上传文件,文件夹,下载文件,文件夹,以及删除功能.配合更详细的..." />
<meta name="keywords" content="腾讯云,COS,对象存储,COSCMD" />
<meta name="generator" content="Typecho 1.2.1" />
<meta name="template" content="handsome" />
<link rel="pingback" href="https://www.ioiox.com/action/xmlrpc" />
<link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://www.ioiox.com/action/xmlrpc?rsd" />
<link rel="wlwmanifest" type="application/wlwmanifest+xml" href="https://www.ioiox.com/action/xmlrpc?wlw" />
<link rel="alternate" type="application/rss+xml" title="腾讯云对象存储 COSCMD 工具安装配置与使用命令  &raquo; 思有云 - IOIOX &raquo; RSS 2.0" href="https://www.ioiox.com/feed/archives/110.html" />
<link rel="alternate" type="application/rdf+xml" title="腾讯云对象存储 COSCMD 工具安装配置与使用命令  &raquo; 思有云 - IOIOX &raquo; RSS 1.0" href="https://www.ioiox.com/feed/rss/archives/110.html" />
<link rel="alternate" type="application/atom+xml" title="腾讯云对象存储 COSCMD 工具安装配置与使用命令  &raquo; 思有云 - IOIOX &raquo; ATOM 1.0" href="https://www.ioiox.com/feed/atom/archives/110.html" />


    
    <script type="text/javascript">

        window['LocalConst'] = {
            //base
            BASE_SCRIPT_URL: 'https://www.ioiox.com/usr/themes/handsome/',
            BLOG_URL: 'https://www.ioiox.com/',
            BLOG_URL_N: 'https://www.ioiox.com',
            STATIC_PATH: 'https://www.ioiox.com/usr/themes/handsome/assets/',
            BLOG_URL_PHP: 'https://www.ioiox.com/',
            VDITOR_CDN: 'https://cdn.jsdelivr.net/npm/vditor@3.9.4',
            ECHART_CDN: 'https://lf6-cdn-tos.bytecdntp.com/cdn/expire-5-y/echarts/4.5.0',
            HIGHLIGHT_CDN: 'https://lf3-cdn-tos.bytecdntp.com/cdn/expire-1-M/highlight.js/10.7.3',

            MATHJAX_SVG_CDN: 'https://cdnjs.loli.net/ajax/libs/mathjax/3.1.2/es5/tex-mml-chtml.min.js',
            THEME_VERSION: '9.2.120230801501',
            THEME_VERSION_PRO: '9.2.1',
            DEBUG_MODE: '0',

            //comment
            COMMENT_NAME_INFO: '必须填写昵称或姓名',
            COMMENT_EMAIL_INFO: '必须填写电子邮箱地址',
            COMMENT_URL_INFO: '必须填写网站或者博客地址',
            COMMENT_EMAIL_LEGAL_INFO: '邮箱地址不合法',
            COMMENT_URL_LEGAL_INFO: '网站或者博客地址不合法',
            COMMENT_CONTENT_INFO: '必须填写评论内容',
            COMMENT_SUBMIT_ERROR: '提交失败，请重试！',
            COMMENT_CONTENT_LEGAL_INFO: '无法获取当前评论(评论已复制到剪切板)，可能原因如下：',
            COMMENT_NOT_IN_FIRST_PAGE:'尝试请前往评论第一页查看',
            COMMENT_NOT_BELONG_CURRENT_TAG:'当前评论不属于该标签，请关闭标签筛选后查看',
            COMMENT_NO_EMAIL:'如果没有填写邮箱则进入审核队列',
            COMMENT_PAGE_CACHED:'页面如果被缓存无法显示最新评论',
            COMMENT_BLOCKED:'评论可能被拦截且无反馈信息',
            COMMENT_AJAX_ERROR:'评论请求失败',
            COMMENT_TITLE: '评论通知',
            STAR_SUCCESS:'点赞成功',
            STAR_REPEAT:'您已点赞',
            STAR_ERROR_NETWORK:'点赞请求失败',
            STAR_ERROR_CODE:'点赞返回未知错误码',
            COOKIE_PREFIX: 'e424ea661f27a10345438ec27d4b7c23',
            COOKIE_PATH: '/',

            //login
            LOGIN_TITLE: '登录通知',
            REGISTER_TITLE: '注册通知',
            LOGIN_USERNAME_INFO: '必须填写用户名',
            LOGIN_PASSWORD_INFO: '请填写密码',
            REGISTER_MAIL_INFO: '请填写邮箱地址',
            LOGIN_SUBMIT_ERROR: '登录失败，请重新登录',
            REGISTER_SUBMIT_ERROR: '注册失败，请稍后重试',
            LOGIN_SUBMIT_INFO: '用户名或者密码错误，请重试',
            LOGIN_SUBMIT_SUCCESS: '登录成功',
            REGISTER_SUBMIT_SUCCESS: '注册成功，您的密码是：',
            CLICK_TO_REFRESH: '点击以刷新页面',
            PASSWORD_CHANGE_TIP: '初始密码仅显示一次，可在管理后台修改密码',
            LOGOUT_SUCCESS_REFRESH: '退出成功，正在刷新当前页面',

            LOGOUT_ERROR: '退出失败，请重试',
            LOGOUT_SUCCESS: '退出成功',
            SUBMIT_PASSWORD_INFO: '密码错误，请重试',
            SUBMIT_TIME_MACHINE:'发表新鲜事',
            REPLY_TIME_MACHINE:'回应',

            //comment
            ChANGYAN_APP_KEY: '',
            CHANGYAN_CONF: '',

            COMMENT_SYSTEM: '0',
            COMMENT_SYSTEM_ROOT: '0',
            COMMENT_SYSTEM_CHANGYAN: '1',
            COMMENT_SYSTEM_OTHERS: '2',
            EMOJI: '表情',
            COMMENT_NEED_EMAIL: '1',
            COMMENT_NEED_URL: '0',
            COMMENT_REJECT_PLACEHOLDER: '居然什么也不说，哼',
            COMMENT_PLACEHOLDER: '说点什么吧……',

            //pjax
            IS_PJAX: '1',
            IS_PAJX_COMMENT: '1',
            PJAX_ANIMATE: 'default',
            PJAX_TO_TOP: '0',
            TO_TOP_SPEED: '100',


            USER_COMPLETED: {"data":""},
            VDITOR_COMPLETED: {"data":""},

            //ui
            OPERATION_NOTICE: '操作通知',
            SCREENSHOT_BEGIN: '正在生成当前页面截图……',
            SCREENSHOT_NOTICE: '点击顶部下载按钮保存当前卡片',
            SCREENSHORT_ERROR: '由于图片跨域原因导致截图失败',
            SCREENSHORT_SUCCESS: '截图成功',

            //music
            MUSIC_NOTICE: '播放通知',
            MUSIC_FAILE: '当前音乐地址无效，自动为您播放下一首',
            MUSIC_FAILE_END: '当前音乐地址无效',
            MUSIC_LIST_SUCCESS: '歌单歌曲加载成功',
            MUSIC_AUTO_PLAY_NOTICE:"即将自动播放，点击<a class='stopMusic'>停止播放</a>",
            MUSIC_API: 'https://www.ioiox.com/action/handsome-meting-api?server=:server&type=:type&id=:id&auth=:auth&r=:r',
            MUSIC_API_PARSE: 'https://www.ioiox.com/action/handsome-meting-api?do=parse',

            //tag
            EDIT:'编辑',
            DELETE:'删除',
            OPERATION_CONFIRMED:'确认',
            OPERATION_CANCELED:'取消',

            TAG_EDIT_TITLE: '编辑提示',
            TAG_EDIT_DESC: '请输入修改后的标签名称（如果输入标签名称已存在，则会合并这两个标签）：',
            TAG_DELETE_TITLE: '删除提示',
            TAG_DELETE_DESC: '确认要删除该标签吗，删除该标签的同时会删除与该标签绑定的评论列表',

            CROSS_DELETE_DESC:'确认删除该条时光机吗？将无法恢复',


            //option
            TOC_TITLE: '文章目录',
            HEADER_FIX: '固定头部',
            ASIDE_FIX: '固定导航',
            ASIDE_FOLDED: '折叠导航',
            ASIDE_DOCK: '置顶导航',
            CONTAINER_BOX: '盒子模型',
            DARK_MODE: '深色模式',
            DARK_MODE_AUTO: '深色模式（自动）',
            DARK_MODE_FIXED: '深色模式（固定）',
            EDITOR_CHOICE: 'origin',
            NO_LINK_ICO:'',
            NO_SHOW_RIGHT_SIDE_IN_POST: '',

            CDN_NAME: '',
            LAZY_LOAD: '',
            PAGE_ANIMATE: '',
            THEME_COLOR: '14',
            THEME_COLOR_EDIT: 'white-white-white',
            THEME_HEADER_FIX: '1',
            THEME_ASIDE_FIX: '1',
            THEME_ASIDE_FOLDED: '',
            THEME_ASIDE_DOCK: '',
            THEME_CONTAINER_BOX: '1',
            THEME_HIGHLIGHT_CODE: '1',
            THEME_TOC: '1',
            THEME_DARK_MODE: 'auto',

            THEME_DARK_MODE_VALUE: 'auto',
            SHOW_SETTING_BUTTON: '1',

            THEME_DARK_HOUR: '18',
            THEME_LIGHT_HOUR: '6',
            THUMB_STYLE: '',
            AUTO_READ_MODE: '',
            SHOW_LYRIC:'',
            AUTO_SHOW_LYRIC:'1',
            //代码高亮
            CODE_STYLE_LIGHT: 'mac_light',
            CODE_STYLE_DARK: 'mac_dark',
            THEME_POST_CONTENT:'2',
            //other
            OFF_SCROLL_HEIGHT: '55',
            SHOW_IMAGE_ALT: '',
            USER_LOGIN: '',
            USE_CACHE: '',
            POST_SPEECH: '1',
            POST_MATHJAX: '',
            SHOW_FOOTER:'1',
            IS_TRANSPARENT:'',
            LOADING_IMG:'',
            PLUGIN_READY:'1',
            PLUGIN_URL:'https://www.ioiox.com/usr/plugins',
            FIRST_SCREEN_ANIMATE:'',
            RENDER_LANG:'zh_CN',
            SERVICE_WORKER_INSTALLED:false,
            CLOSE_LEFT_RESIZE:'',
            CLOSE_RIGHT_RESIZE:'',
            CALENDAR_GITHUB:'',
            LATEST_POST_TIME:'1712453827',
            LATEST_TIME_COMMENT_TIME:'1715651821',
            LEFT_LOCATION: '1',

            INPUT_NEW_TAG:'输入结束后加空格创建新标签'
        };

        function clearCache(needRefresh = false) {
            window.caches && caches.keys && caches.keys().then(function (keys) {
                keys.forEach(function (key) {
                    console.log("delete cache",key);
                    caches.delete(key);
                    if (needRefresh){
                        window.location.reload();
                    }
                });
            });
        }

        function unregisterSW() {
            navigator.serviceWorker.getRegistrations()
                .then(function (registrations) {
                    for (var index in registrations) {
                        // 清除缓存
                        registrations[index].unregister();
                    }
                });
        }

        function registerSW() {
            navigator.serviceWorker.register(LocalConst.BLOG_URL + 'sw.min.js?v=9.2.120230801501')
                .then(function (reg) {
                    if (reg.active){
                        LocalConst.SERVICE_WORKER_INSTALLED = true;
                    }
                }).catch(function (error) {
                console.log('cache failed with ' + error); // registration failed
            });
        }

        if ('serviceWorker' in navigator) {
            const isSafari = /Safari/.test(navigator.userAgent) && !/Chrome/.test(navigator.userAgent);
            if (LocalConst.USE_CACHE && !isSafari) {//safari的sw兼容性较差目前关闭
                registerSW();
            } else {
                unregisterSW();
                clearCache();
            }
        }
    </script>

    <!-- 第三方CDN加载CSS -->
    <link href="https://lf3-cdn-tos.bytecdntp.com/cdn/expire-1-M/twitter-bootstrap/3.3.4/css/bootstrap.min.css" rel="stylesheet">


    <!-- 本地css静态资源 -->

        <link rel="stylesheet" href="https://www.ioiox.com/usr/themes/handsome/assets/css/origin/function.min.css?v=9.2.120230801501" type="text/css"/>
    <link rel="stylesheet"
          href="https://www.ioiox.com/usr/themes/handsome/assets/css/handsome.min.css?v=9.2.120230801501"
          type="text/css"/>

        
    
    <!--主题组件css文件加载-->
    
    <!--引入英文字体文件-->
            <link rel="stylesheet preload" href="https://www.ioiox.com/usr/themes/handsome/assets/css/features/font.min.css?v=9.2.120230801501" as="style"/>
    
    <style type="text/css">
        
        html.bg {
        background: #EFEFEF
        }
        .cool-transparent .off-screen+#content {
        background: #EFEFEF
        }
@media (max-width:767px){
    html.bg {
        background: 
        }
        .cool-transparent .off-screen+#content {
        background: 
        }
}
.blog-post .panel:not(article) {
    transition: all 0.3s;
}

.blog-post .panel:not(article):hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 10px rgba(73, 90, 47, 0.47);
}    </style>

    <!--全站jquery-->
    <script src="https://lf26-cdn-tos.bytecdntp.com/cdn/expire-1-M/jquery/2.2.4/jquery.min.js"></script>
    <script>
        if (LocalConst.USE_CACHE && !window.jQuery){
            console.log("jQuery is Bad",document.cookie.indexOf("error_cache_refresh"));
            if (document.cookie && document.cookie.indexOf("error_cache_refresh")===-1){//半个小时内没有刷新过
                console.log("jQuery is Bad，we need clear cache,retry refresh");
                document.cookie = "error_cache_refresh=1;max-age=1800;path=/";
                clearCache(true);
                if ('serviceWorker' in navigator) {
                    //todo 尝试注销sw后再启用sw
                }
            }
        }
    </script>
    <!--网站统计代码-->
    <!-- Google tag (gtag.js) -->
<script async src="https://ga.ioiox.net/gtag/js?id=G-F00FY0X9ZD"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-F00FY0X9ZD');
</script>

<script defer src="https://umami.ioiox.net/script.js" data-website-id="fd831f41-8d2e-4189-9f92-cac11a4e15be"></script>

<!-- CSS -->
<link href="https://cdn.bootcdn.net/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">

<!-- favicon -->
<link rel=”icon” href=”/favicon.ico” mce_href=”/favicon.ico” type=”image/x-icon”>
<link rel=”shortcut icon” href=”/favicon.ico” mce_href=”/favicon.ico” type=”image/x-icon”>

</head>

<body id="body" class="fix-padding skt-loading">

	<!-- aside -->
	  
  <div id="alllayout" class="app app-aside-fix container app-header-fixed ">  <!-- headnav -->
  <header id="header" class="app-header navbar box-shadow-bottom-lg fix-padding" role="menu">
    <!-- navbar header（交集处） -->
    <div id="header_left" class="text-ellipsis navbar-header bg-white">
    <button class="pull-right visible-xs" ui-toggle-class="show animated animated-lento fadeIn" target=".navbar-collapse">
        <span class="menu-icons"><i data-feather="search"></i></span>
    </button>
    <button class="pull-left visible-xs" ui-toggle-class="off-screen animated" target=".app-aside" ui-scroll="app">
        <span class="menu-icons"><i data-feather="menu"></i></span>
    </button>
    <!-- brand -->
    <a href="https://www.ioiox.com/" class="navbar-brand text-lt">
        <span id="navbar-brand-day">
                                                <i data-feather="home"></i>
                            <span class="hidden-folded m-l-xs">IOIOX</span>
                    </span>
            </a>
    <!-- / brand -->
    </div>
    <!-- / navbar header -->

    <!-- navbar collapse（顶部导航栏） -->
    <div id="header_right" class="collapse pos-rlt navbar-collapse bg-white">
    <!-- statitic info-->
        <ul class="nav navbar-nav hidden-sm">
        <li class="dropdown pos-stc">
            <a id="statistic_pane" data-status="false" href="#" data-toggle="dropdown" class="dropdown-toggle feathericons dropdown-toggle"
               aria-expanded="false">
                <i data-feather="pie-chart"></i>
                <span class="caret"></span>
            </a>
            <div class="dropdown-menu wrapper w-full bg-white">
                <div class="row">
                    <div class="col-sm-8 b-l b-light">
                        <div class="m-l-xs m-t-xs  font-bold">动态日历                        </div>
                        <div class="text-muted m-l-xs " style="font-size: 12px">统计近10个月的博主文章和评论数目</div>
                        <div class="text-center">
                            <nav class="loading-echart text-center m-t-lg m-b-lg">
                                <p class="infinite-scroll-request"><i class="animate-spin fontello fontello-refresh"></i>Loading...</p>
                            </nav>
                            <div id="post-calendar" class="top-echart hide"></div>
                        </div>
                    </div>
                    <div class="col-sm-4 b-l b-light">
                        <div class="m-l-xs m-t-xs m-b-sm font-bold">分类雷达图</div>
                        <div class="text-center">
                            <nav class="loading-echart text-center m-t-lg m-b-lg">
                                <p class="infinite-scroll-request"><i class="animate-spin fontello fontello-refresh"></i>Loading...</p>
                            </nav>
                            <div id="category-radar" class="top-echart hide"></div>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-sm-4 b-l b-light">
                        <div class="m-l-xs m-t-xs m-b-sm font-bold">发布统计图</div>
                        <div class="text-center">
                            <nav class="loading-echart text-center m-t-lg m-b-lg">
                                <p class="infinite-scroll-request"><i class="animate-spin fontello fontello-refresh"></i>Loading...</p>
                            </nav>
                            <div id="posts-chart" class="top-echart hide"></div>
                        </div>
                    </div>
                    <div class="col-sm-4 b-l b-light">
                        <div class="m-l-xs m-t-xs m-b-sm font-bold">分类统计图</div>
                        <div class="text-center">
                            <nav class="loading-echart text-center m-t-lg m-b-lg">
                                <p class="infinite-scroll-request"><i class="animate-spin fontello fontello-refresh"></i>Loading...</p>
                            </nav>
                            <div id="categories-chart" class="top-echart hide"></div>
                        </div>
                    </div>
                    <div class="col-sm-4 b-l b-light">
                        <div class="m-l-xs m-t-xs m-b-sm font-bold">标签统计图</div>
                        <div class="text-center">
                            <nav class="loading-echart text-center m-t-lg m-b-lg">
                                <p class="infinite-scroll-request"><i class="animate-spin fontello fontello-refresh"></i>Loading...</p>
                            </nav>
                            <div id="tags-chart" class="top-echart hide"></div>
                        </div>
                    </div>
                </div>
            </div>
        </li>
    </ul>
    
    <!-- search form -->

    <form id="searchform1" class="searchform navbar-form navbar-form-sm navbar-left shift" method="post"
          role="search">
        <div class="form-group">
            <div class="input-group rounded bg-white-pure box-shadow-wrap-normal">
                <input  autocomplete="off" id="search_input" type="search" name="s" class="transparent rounded form-control input-sm no-borders padder" required placeholder="搜索（Ctrl + K）">
                <!--搜索提示-->
                <ul id="search_tips_drop" class="search_modal_list overflow-y-auto small-scroll-bar dropdown-menu hide" style="display:
                 block;top:
                30px; left: 0px;">
                </ul>
                <span id="search_submit" class="transparent input-group-btn">
                  <button  type="submit" class="transparent btn btn-sm">
                      <span class="feathericons icon-search"><i data-feather="search"></i></span>
                      <span class="feathericons animate-spin  hide spin-search"><i
                                  data-feather="loader"></i></span>
                  </button>
              </span>
            </div>
            <a class="btn btn-sm  btn-icon open_search_modal_mobile"><i data-feather="external-link"></i></a>
        </div>
    </form>
    <a href="" style="display: none" id="searchUrl"></a>
    <!-- / search form -->
        <ul class="nav navbar-nav navbar-right">
                <li class="dropdown"><a target="_blank" href="https://shop.ioiox.com" class="feathericons dropdown-toggle" ><i><i data-feather="shopping-cart"></i></i><span class="visible-xs-inline">小店</span></a></li><li class="dropdown"><a target="_blank" href="https://freefrp.net" class="feathericons dropdown-toggle" ><i><i data-feather="globe"></i></i><span class="visible-xs-inline">FRP</span></a></li><li class="dropdown"><a target="_blank" href="https://rssforever.com" class="feathericons dropdown-toggle" ><i><i data-feather="rss"></i></i><span class="visible-xs-inline">RSS</span></a></li><li class="dropdown"><a target="_blank" href="https://t.me/ioioxcom" class="feathericons dropdown-toggle" ><i><i data-feather="send"></i></i><span class="visible-xs-inline">TG群</span></a></li><li class="dropdown"><a target="_blank" href="https://github.com/stilleshan" class="feathericons dropdown-toggle" ><i><i data-feather="github"></i></i><span class="visible-xs-inline">仓库</span></a></li>                    </ul>
    </div>
    <!-- / navbar collapse -->
</header>
  <div id="search_modal" class="modal fade" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel"> 
   <div class="modal-dialog modal-lg" role="document"> 
    <div class="modal-content box-shadow-wrap-lg"> 
     <div class="modal-header"> 
        <div class="form-group">
            <div class="input-group box-shadow-wrap-normal slight-border">
                <input  autocomplete="off" id="search_modal_input" type="search" name="s" class="transparent form-control input-sm padder" required placeholder="输入关键词搜索…">
                <!--搜索提示-->
                
                <span id="search_modal_submit" class="transparent input-group-btn">
                  <button  type="submit" class="transparent btn btn-sm">
                      <span class="feathericons icon-search"><i data-feather="search"></i></span>
                      <span class="feathericons animate-spin  hide spin-search"><i
                                  data-feather="loader"></i></span>
                  </button>
              </span>
            </div>
        </div>      
     </div> 
     <div class="modal-body"> 
      <div class="tab-container post_tab"> 
       <ul class="nav no-padder b-b scroll-hide" role="tablist"> 
        <li class="nav-item active" role="presentation"><a class="nav-link active" style="" data-toggle="tab" role="tab" data-target="#post_search_content">文章</a></li> 
        <li class="nav-item " role="presentation"><a class="nav-link " style="" data-toggle="tab" role="tab" data-target="#time_search_content">时光机</a></li> 
       </ul> 
       <div class="tab-content no-border no-padder">
       <div role="tabpanel" id="post_search_content" class="tab-pane fade active in">
       <ul id="search_modal_list" class="search_modal_list overflow-y-auto small-scroll-bar dropdown-menu">
                </ul>
        </div>
        
        
       <div role="tabpanel" id="time_search_content" class="tab-pane fade">
       <ul id="time_search_modal_list" class="search_modal_list overflow-y-auto small-scroll-bar dropdown-menu">
                </ul>
        </div>
                
       </div>
       <!--tab-content--> 
      </div> 
      <!--tab-container-->
     </div> 
     <!--modal-body--> 
    </div>
    <!--modal-content--> 
   </div>
   <!--modal-dialog--> 
  </div>
  <!--modal-->
  <!-- / headnav -->

  <!--选择侧边栏的颜色-->
  <aside id="aside" class="gpu-speed app-aside hidden-xs bg-white">  <!--<aside>-->
        <div class="aside-wrap" layout="column">
        <div class="navi-wrap scroll-y scroll-hide" flex>
          <!-- user -->
          <div class="clearfix hidden-xs text-center hide  show" id="aside-user">
            <div class="dropdown wrapper m-t-sm ">
                <div ui-nav>
                          <a href="https://www.ioiox.com/stille.html">
                            <span class="thumb-lg w-auto-folded avatar  ">
                  <img src="https://www.ioiox.com/avatar.jpg" class="img-full img-circle">
                    <i class="md b-white bottom hide" id="auto_status" data-toggle="tooltip" data-placement="left" title=""></i>
                </span>
              </a>
                </div>
              <a href="#" data-toggle="dropdown" class="dropdown-toggle hidden-folded  ">
                <span class="clear">
                  <span class="block">
                    <strong class="font-bold text-lt">Stille</strong>
                    <b class="caret"></b>
                  </span>
                  <span class="text-muted text-xs block">以不折腾为目标的折腾,才是折腾的最高境界!</span>
                </span>
              </a>
              <!-- dropdown -->
              <ul class="dropdown-menu animated fadeInRight w hidden-folded no-padder">
                <li class="wrapper b-b m-b-sm bg-info m-n">
                  <span class="arrow top hidden-folded arrow-info"></span>
                  <div>
                                                <p>晚上好，注意早点休息</p>
                                  </div>
                  <div class="progress progress-xs m-b-none dker">
                    <div class="progress-bar bg-white" data-toggle="tooltip" data-original-title="时间已经度过0.00%" style="width: 0.00%"></div>
                  </div>
                </li>
              </ul>
              <!-- / dropdown -->
            </div>
          </div>
          <!-- / user -->

          <!-- nav -->
          <nav ui-nav class="navi clearfix">
            <ul class="nav">
             <!--index-->
                <li class="hidden-folded padder m-t m-b-sm text-muted text-xs">




                <!-- 注释导航字样 stille -->
<!--                <span>--><!--</span>-->
                <!-- 注释导航字样 stille -->




              </li>
                                          <!--主页-->
              <li>
                <a href="https://www.ioiox.com/" class="auto">
                    <span class="nav-icon"><i data-feather="home"></i></span>
                    <span>首页</span>
                </a>
              </li>
              <!-- /主页 -->




              <!--以下-stille手动复制-分类category-->
              <!--stille 001 分类category-->
                            <li >
                <a class="auto">
                  <span class="pull-right text-muted">
                    <i class="fontello icon-fw fontello-angle-right text"></i>
                    <i class="fontello icon-fw fontello-angle-down text-active"></i>
                  </span>
                  <!-- <i class="glyphicon glyphicon-th"></i>-->
                    <span class="nav-icon"><i data-feather="grid"></i></span>

                    <span>分类</span>
                </a>
                <ul class="nav nav-sub dk">
                  <li class="nav-sub-header">
                    <a>
                      <span>分类</span>
                    </a>
                  </li>
                  <!--循环输出分类-->
                    <li><a href="https://www.ioiox.com/category/default/"><b class="badge pull-right">7</b><span>日常资讯</span></a></li><li><a href="https://www.ioiox.com/category/digital/"><b class="badge pull-right">7</b><span>数字生活</span></a></li><li><a href="https://www.ioiox.com/category/ops/"><b class="badge pull-right">58</b><span>运维部署</span></a></li><li><a href="https://www.ioiox.com/category/tech/"><b class="badge pull-right">54</b><span>技术教程</span></a></li><li><a class="auto"><span class="pull-right text-muted">
                    <i class="fontello icon-fw fontello-angle-right text"></i>
                    <i class="fontello icon-fw fontello-angle-down text-active"></i>
                  </span><span>群辉专栏</span></a><ul class="nav nav-sub dk child-nav"><li><a href="https://www.ioiox.com/category/%E5%9F%BA%E7%A1%80%E6%9C%8D%E5%8A%A1/"><b class="badge pull-right">6</b><span>基础服务</span></a></li><li><a href="https://www.ioiox.com/category/%E7%BD%91%E7%BB%9C%E6%9C%8D%E5%8A%A1/"><b class="badge pull-right">17</b><span>网络服务</span></a></li><li><a href="https://www.ioiox.com/category/%E5%A5%97%E4%BB%B6%E6%9C%8D%E5%8A%A1/"><b class="badge pull-right">9</b><span>套件服务</span></a></li><li><a href="https://www.ioiox.com/category/%E9%AB%98%E7%BA%A7%E6%9C%8D%E5%8A%A1/"><b class="badge pull-right">15</b><span>高级服务</span></a></li></ul></li>                </ul>
              </li>
              <!--stille 002 独立页面pages-->
                <li>
                <a class="auto">
                  <span class="pull-right text-muted">
                    <i class="fontello icon-fw fontello-angle-right text"></i>
                    <i class="fontello icon-fw fontello-angle-down text-active"></i>
                  </span>
                    <span class="nav-icon"><i data-feather="file"></i></span>
                  <span>页面</span>
                </a>
                <ul class="nav nav-sub dk">
                  <li class="nav-sub-header">
                    <a data-no-instant>
                      <span>页面</span>
                    </a>
                  </li><!--这个字段不会被显示出来-->
                  <!--循环输出独立页面-->
                                                                                   <li><a href="https://www.ioiox.com/msg.html"><span>留言板</span></a></li>
                                                                 <li><a href="https://www.ioiox.com/archives.html"><span>归档库</span></a></li>
                                                                 <li><a href="https://www.ioiox.com/stille.html"><span>关于我</span></a></li>
                                   </ul>
              </li>
              <!--stille 003 群晖专栏pages-->
              <li>
                <a class="auto">
                  <span class="pull-right text-muted">
                    <i class="fontello icon-fw fontello-angle-right text"></i>
                    <i class="fontello icon-fw fontello-angle-down text-active"></i>
                  </span>
                  <span class="nav-icon"><i data-feather="server"></i></span>
                  <span>群晖</span>
                </a>
                <ul class="nav nav-sub dk">
                  <li class="nav-sub-header">
                    <a data-no-instant>
                      <span>群晖</span>
                    </a>
                  </li>
                    <li><a href="https://www.ioiox.com/synology.html"><span>专栏首页</span></a></li>
                    <li><a href="https://www.ioiox.com/category/基础服务/"><span>基础服务</span></a></li>
                    <li><a href="https://www.ioiox.com/category/网络服务/"><span>网络服务</span></a></li>
                    <li><a href="https://www.ioiox.com/category/套件服务/"><span>套件服务</span></a></li>
                    <li><a href="https://www.ioiox.com/category/高级服务/"><span>高级服务</span></a></li>
                 </ul>
              </li>
              <!--以上-stille手动复制-分类category-->






                            <li> <a target="_blank" href="https://shop.ioiox.com" 
class ="auto"><span class="nav-icon" ><i data-feather="shopping-cart"></i></span><span >小店</span></a></li><li> <a target="_blank" href="https://freefrp.net" 
class ="auto"><span class="nav-icon" ><i data-feather="globe"></i></span><span >FRP</span></a></li><li> <a target="_blank" href="https://rssforever.com" 
class ="auto"><span class="nav-icon" ><i data-feather="rss"></i></span><span >RSS</span></a></li><li> <a target="_blank" href="https://t.me/ioioxcom" 
class ="auto"><span class="nav-icon" ><i data-feather="send"></i></span><span >TG群</span></a></li><li> <a target="_blank" href="https://github.com/stilleshan" 
class ="auto"><span class="nav-icon" ><i data-feather="github"></i></span><span >仓库</span></a></li><li> <a target="_self" href="https://www.ioiox.com/about.html" 
class ="auto"><span class="nav-icon" ><i data-feather="info"></i></span><span >关于</span></a></li>                




              <!--全站友情链接 下移 stille 改动 -->
              <!--友情链接-->
              <li>
                <a class="auto">
                  <span class="pull-right text-muted">
                    <i class="fontello icon-fw fontello-angle-right text"></i>
                    <i class="fontello icon-fw fontello-angle-down text-active"></i>
                  </span>
                    <span class="nav-icon"><i data-feather="user"></i></span>
                  <span>友链</span>
                </a>
                <ul class="nav nav-sub dk">
                  <li class="nav-sub-header">
                    <a data-no-instant>
                      <span>友链</span>
                    </a>
                  </li>
                  <!--使用links插件，输出全站友链-->
                 <li data-original-title="Typecho官方网站" data-toggle="tooltip" 
data-placement="top"><a rel='noopener' href="http://typecho.org/" target="_blank"><span>Typecho官方网站</span></a></li><li data-original-title="群晖官方网站" data-toggle="tooltip" 
data-placement="top"><a rel='noopener' href="https://www.synology.com" target="_blank"><span>群晖官方网站</span></a></li><li data-original-title="小楼一夜听风雨" data-toggle="tooltip" 
data-placement="top"><a rel='noopener' href="https://sunpma.com" target="_blank"><span>SunPma'Blog</span></a></li><li data-original-title="心有猛虎，细嗅蔷薇。" data-toggle="tooltip" 
data-placement="top"><a rel='noopener' href="https://www.quchao.net" target="_blank"><span>Mark's Blog</span></a></li><li data-original-title="一个想做天才的小白" data-toggle="tooltip" 
data-placement="top"><a rel='noopener' href="https://www.87csn.com" target="_blank"><span>爱好者博客</span></a></li><li data-original-title="一个神秘的人" data-toggle="tooltip" 
data-placement="top"><a rel='noopener' href="https://traderboris.com" target="_blank"><span>Boris的交易世界</span></a></li><li data-original-title="一个神秘的人" data-toggle="tooltip" 
data-placement="top"><a rel='noopener' href="https://www.bboy.app/" target="_blank"><span>Bboysoul's Blog</span></a></li>                </ul>
              </li>
              <!--     全站友情链接 下移 stille 改动       -->








              
            </ul>
          </nav>
          <!-- nav -->
            <!--left_footer-->
                            <div id="left_footer" class="social_icon box-shadow-wrap-normal aside-items b-normal nav-xs lt">
                    <a data-container="body" data-toggle="tooltip" data-placement="top" data-original-title="评论RSS订阅"
                           target="_blank"  href="https://www.ioiox.com/feed/comments/" class="aside-item btn btn-sm  btn-icon">
                            <span class="left-bottom-icons block"><i data-feather="message-square"></i></span>
                        </a><a data-container="body" data-toggle="tooltip" data-placement="top" data-original-title="文章RSS订阅"
                           target="_blank"  href="https://www.ioiox.com/feed/" class="aside-item btn btn-sm  btn-icon">
                            <span class="left-bottom-icons block"><i data-feather="rss"></i></span>
                        </a>                </div>
                    </div>
          <!--end of .navi-wrap-->
      </div><!--.aside-wrap-->
  </aside>
<!-- content -->

<div id="content" class="app-content">
    <div class="resize-pane">
        <div id="trigger_left_content" class="trigger_content"><div class="trigger_drag_content"></div></div>
        <div id="trigger_left_button" data-placement="right" data-toggle="tooltip" data-original-title="点击展开左侧边栏" class="normal-widget resize-pane-trigger box-shadow-wrap-lg"><i data-feather="sidebar"></i></div>
    </div>
    <!--loading animate-->
    <div id="loading" class="butterbar active hide">
            <span class="bar"></span>
        </div>





	<!-- / aside -->
<style>
    #post-content{
        font-size: 14px;
    }
</style>
<!-- <div id="content" class="app-content"> -->
   <a class="off-screen-toggle hide"></a>
   <main class="app-content-body ">
    <div class="hbox hbox-auto-xs hbox-auto-sm">
    <!--文章-->
     <div class="col center-part gpu-speed" id="post-panel">
         <!--生成分享图片必须的HTML结构-->
             <!--标题下的一排功能信息图标：作者/时间/浏览次数/评论数/分类-->
      
        <header id="small_widgets" class="bg-light lter wrapper-md">
             <h1 class="entry-title m-n font-thin text-black l-h">腾讯云对象存储 COSCMD 工具安装配置与使用命令 <a class="plus-font-size" data-toggle="tooltip" data-original-title="点击改变文章字体大小"><i data-feather="type"></i></a><a class="speech-button m-l-sm superscript" data-toggle="tooltip" data-original-title="朗读文章"><i data-feather="mic"></i></a><a data-morphing style="vertical-align: -1px;" id="morphing" data-src="#morphing-content" href="javascript:;" class="read_mode superscript m-l-sm" 
data-toggle="tooltip" data-placement="right" data-original-title="阅读模式"><i data-feather="book-open"></i></a></h1>       <!--文章标题下面的小部件-->
                  <ul  class="entry-meta text-muted list-inline m-b-none small
             post-head-icon">
             <!--作者-->
             <li class="meta-author"><span class="post-icons"><i data-feather="user"></i></span><span
                         class="sr-only">博主：</span> <a class="meta-value" href="https://www.ioiox.com/author/1/" rel="author"> Stille</a></li>
             <!--发布时间-->
             <li class="meta-date" data-toggle="tooltip" data-html="true" data-original-title="2020 年 07 月 08 日 11 : 40  AM"><span class="post-icons"><i data-feather="clock"></i></span><span class="sr-only">发布时间：</span><time class="meta-value">2020 年 07 月 08 日</time></li>
             <!--浏览数-->
             <li class="meta-views"><span class="post-icons"><i data-feather="eye"></i></span><span class="meta-value">8752&nbsp;次浏览</span></li>
                              <!--评论数-->
                 <li class="meta-comments"><span class="post-icons"><i data-feather="message-circle"></i></span><a
                             class="meta-value" href="#comments">1 条评论</a></li>
             
             <!--文字数目-->
             <li class="meta-word"><span class="post-icons"><i data-feather="pen-tool"></i></span><span class="meta-value">1884字数</span></li>
             <!--分类-->
             <li class="meta-categories"><span class="post-icons"><i data-feather="hash"></i></span><span class="sr-only">分类：</span> <span class="meta-value" id="post_category"><a href="https://www.ioiox.com/category/tech/">技术教程</a></span></li>
         </ul>
      </header>
      <div class="wrapper-md">
	   <ol class="breadcrumb bg-white-pure" itemscope=""><li>
                 <a href="https://www.ioiox.com/" itemprop="breadcrumb" title="返回首页" data-toggle="tooltip"><span class="home-icons"><i data-feather="home"></i></span>首页</a>
             </li><li class="active">正文&nbsp;&nbsp;</li></ol>       <!--博客文章样式 begin with .blog-post-->
       <div id="postpage" class="blog-post">
        <article class="single-post panel">
        <!--文章页面的头图-->
        <div class="entry-thumbnail" aria-hidden="true"><div class="item-thumb lazy"  style="background-image: url(https://www.ioiox.com/usr/uploads/2020/07/1192297397.jpg)"></div></div>         <!--文章内容-->
         <div id="post-content" class="wrapper-lg">

             <script>
        LocalConst.POST_MATHJAX = ""
        LocalConst.EDITOR_CHOICE = "origin"
</script><div class="entry-content l-h-2x" id="md_handsome_origin"><h2>前言</h2><p>COSCMD 工具是一款腾讯云 COS 的命令行操作工具,能方便的在 Linux 服务器上管理对象存储 COS 中的桶文件,支持上传文件,文件夹,下载文件,文件夹,以及删除功能.配合更详细的参数例如 md5 比对,跳过,删除等可以很方便的配置定时备份服务器上的文件到 COS 中.本文将简单介绍在 Linux 系统中的安装,配置和常规上传下载命令,更详细的用法请参考下文中的相关参考链接.</p><p><div class="tip inlineBlock success">本文为<a href="https://www.ioiox.com/stille.html" target="_blank"> Stille </a>原创文章.经实践,测试,整理发布.如需转载请联系作者获得授权,并注明转载地址.</div><hr><h2>安装</h2><h3>环境依赖</h3><ul><li>Python 2.7/3.5/3.6</li><li>最新版本的 pip</li></ul><h3>安装命令</h3><pre><code class="lang-bash">yum -y install python-pip
python -m pip install --upgrade pip    
pip install -I requests
pip install coscmd</code></pre><p>&nbsp;&nbsp;<br><img src="https://www.ioiox.com/usr/uploads/2020/04/4267100629.png" alt="" title="" style=""></p><h2>配置</h2><h3>获取存储痛信息</h3><h4>登录腾讯云 - 控制台 - 对象存储 - 存储桶获取相关信息</h4><ul><li>BucketName-APPID : <code>test-1250000000</code> 为存储桶名称</li><li>区域地址 : <code>https://cos.ap-shanghai.myqcloud.com</code> 存储桶所在的区域域名.</li></ul><h4>登录腾讯云 - 控制台 - 访问管理</h4><p>创建子账号并赋予 COS 相关权限,生成<code>SecretId</code>和<code>SecretKey</code>.</p><ul><li>SecretId : XXXXXX</li><li>SecretKey : XXXXXX</li></ul><h3>配置密钥</h3><pre><code class="lang-bash">coscmd config -a AKIxxxxxxxxxxxxxx -s xxxxxxxxxxxxxxxxx -b test-1250000000 -r ap-shanghai</code></pre><p>&nbsp;&nbsp;<br><img src="https://www.ioiox.com/usr/uploads/2020/04/4267100629.png" alt="" title="" style=""></p><h2>命令</h2><h3>参数</h3><pre><code class="lang-bash">-f
# 强制跳过提示
-r
# 递归子目录
-s
# 比对 md5
--delete
# 对比并删除文件
--ignore
# 忽略文件或文件夹,支持 *.* 或文件夹路径.</code></pre><h3>下载文件 / 文件夹</h3><pre><code class="lang-bash">coscmd download -f -s /test/test.txt /data/
# 下载文件
coscmd download -rf -s --delete /test /data/
# 下载文件夹
# 结尾含 / 则下载桶中 /test 整个目录至本地 /data 目录之下,路径为 /data/test
# 结尾不含 / 则下载桶中 /test 目录内所有子目录和文件至本地 /data 目录之下</code></pre><h3>上传文件 / 文件夹</h3><pre><code class="lang-bash">coscmd upload -f -s /test/test.txt /data/
# 上传文件
coscmd upload -rf -s --delete /test /data/
# 上传文件夹
# 结尾含 / 则上传本地 /test 整个目录至桶中 /data 目录之下,路径为 /data/test
# 结尾不含 / 则上传本地 /test 目录内所有子目录和文件至桶中 /data 目录之下</code></pre><hr><h2>结语</h2><p>推荐当服务器也是腾讯云时,可以创建与服务器同区域的对象存储,此时两者为内网传输速度,并且 COS 不计下行流量,搭配 crontab 做定时备份任务非常高效稳定.其他更多相关信息请参考以下链接:<br><div class="tip inlineBlock share"><span class="external-link"><a class="no-external-link" href="https://cloud.tencent.com/document/product/436/10976" target="_blank"><i data-feather="external-link"></i>腾讯云 COSCMD 工具</a></span><br><span class="external-link"><a class="no-external-link" href="https://cloud.tencent.com/document/product/436/30744" target="_blank"><i data-feather="external-link"></i>COSCMD 工具类常见问题</a></span></div><hr class="content-copyright" style="margin-top:50px" /><div align="center"><p class="content-copyright"><div class="tip inlineBlock success">

本文为<a class="content-copyright" href="https://www.ioiox.com/stille.html"> Stille </a>原创文章.经实践,测试,整理发布.如需转载请联系作者获得授权,并注明转载地址.</p>
                    <p align="left">本文链接 <a class="content-copyright" href="https://www.ioiox.com/archives/110.html">https://www.ioiox.com/archives/110.html</a>
</div></p></div></div>

                              <!--文章页脚的广告位-->
                 <a
  href="https://go.ssrdog.com/?code=gBXmmXyG"
  target="_blank"
  style="color: #ff5733"
  >晚高峰稳定 4K 的 IPLC 机场 解锁各流媒体 支持 ChatGPT.</a
>
<a href="https://go.ssrdog.com/?code=gBXmmXyG" target="_blank">
  <img
    src="https://i.ioiox.com/2024/01/18/1705546275005TneRkS.jpg"
    alt="晚高峰稳定 4K 的 IPLC 机场 解锁各流媒体 支持 ChatGPT."
  />
</a>
<a
  href="https://www.ioiox.com/archives/171.html"
  target="_blank"
  style="color: #ff5733"
  >RedteaGO - 最划算的大陆漫游 eSim 流量卡，原生境外 IP，注册就送 3 刀。</a
>
<br />
<a href="https://www.ioiox.com/archives/171.html" target="_blank">
  <img
    src="https://i.ioiox.com/2024/01/18/1705546181429fGLBqz.jpg"
    alt="RedteaGO - 最划算的大陆漫游 eSim 流量卡，原生境外 IP，注册就送 3 刀。"
  />
</a>
                          <!--文章的页脚部件：打赏和其他信息的输出-->
             <div class="show-foot"><div class="copyright" data-toggle="tooltip" data-html="true" data-original-title="转载请保留本文转载地址，著作权归作者所有"><span>© 允许规范转载</span>
                 </div>
             </div>
                         <!--打赏模块-->
             <div class="support-author">
                 <button id="support_author"  data-toggle="modal" data-target="#myModal" class="box-shadow-wrap-lg btn_post_footer btn btn-pay btn-yellow btn-rounded"><svg fill="none" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" class="icon" aria-hidden="true"><path d="M10.084 7.606c3.375-1.65 7.65-1.154 10.493 1.487 3.497 3.25 3.497 8.519 0 11.77-3.498 3.25-9.167 3.25-12.665 0-.897-.834-2.488-2.96-2.488-5.085" stroke="currentColor" stroke-width="1.4" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"></path><path d="M17.392 14.78s1.532-1.318-.053-2.79c-1.585-1.473-3.17-.404-3.719.403-.549.807.495 2.082.93 2.69.434.61 1.364 2.182-.054 3.202-1.417 1.012-3.002.658-4.153-.708-1.15-1.367-.602-3.365 0-3.924M17.338 11.982l1.159-1.076M9.87 18.922l.937-.871" stroke="currentColor" stroke-width="1.4" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"></path><path d="M.8 1.205s7.15 4.673 8.773 6.182c1.623 1.508 3.231 4.008 1.616 5.509-2.195 2.04-4.054.595-6.737-.75-.884-.447-3.15-1.777-3.15-1.777M10.136.9l1.047 3.188" stroke="currentColor" stroke-width="1.4" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"></path></svg><span>打赏</span></button> <div id="myModal" class="modal fade bs-example-modal-sm" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel">
                 <div class="modal-dialog modal-sm" role="document">
                     <div class="modal-content box-shadow-wrap-lg">
                         <div class="modal-header box-shadow-bottom-normal">
                             <button type="button" class="close" data-dismiss="modal"><i style="vertical-align: bottom;" data-feather="x-circle"></i></button>
                             <h4 class="modal-title">赞赏作者</h4>
                         </div>
                         <div class="modal-body">
                             <div class="solid-tab tab-container post_tab">
                                <ul class="nav no-padder b-b scroll-hide" role="tablist"> <li class="nav-item active" role="presentation"><a class="nav-link active" style="" data-toggle="tab"  role="tab" data-target="#alipay_author"><i class="iconfont icon-alipay" aria-hidden="true"></i>支付宝</a></li><li class="nav-item " role="presentation"><a class="nav-link " style="" data-toggle="tab"  role="tab" data-target="#wechatpay_author"><i class="iconfont icon-wechatpay" aria-hidden="true"></i>微信</a></li>        </ul>
                                <div class="tab-content no-border"><div role="tabpanel" id="alipay_author" class="tab-pane fade active in">
                            <img noGallery class="pay-img tab-pane" id="alipay_author" role="tabpanel" src="https://www.ioiox.com/usr/themes/handsome/assets/img/loading.svg" data-original="https://www.ioiox.com/alipay.jpg" />
                            </div><div role="tabpanel" id="wechatpay_author" class="tab-pane fade  ">
                            <img noGallery  class="pay-img tab-pane" id="wechatpay_author" role="tabpanel" src="https://www.ioiox.com/usr/themes/handsome/assets/img/loading.svg" data-original="https://www.ioiox.com/wechatpay.jpg" />
                            </div>    </div><!--tab-content-->
                             </div> <!--tab-container--></div> <!--modal-body-->
                         </div><!--modal-content-->
                     </div><!--modal-dialog-->
                 </div><!--modal-->
        <button id="star_post" data-cid="1338" class="box-shadow-wrap-lg btn_post_footer like_button btn btn-pay btn-rounded">
                 <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="shake-little unlike_svg feather feather-thumbs-up"><path d="M14 9V5a3 3 0 0 0-3-3l-4 9v11h11.28a2 2 0 0 0 2-1.7l1.38-9a2 2 0 0 0-2-2.3zM7 22H4a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h3"></path></svg>
                 <div class="circle-rounded"></div>
                 <svg class="liked_svg" style="transform: scale(2.2);" xmlns="http://www.w3.org/2000/svg" viewBox="30 30 60 60" width="60" height="60" preserveAspectRatio="xMidYMid meet">
                    <g clip-path="url(#__lottie_element_1061)">
                        <g style="display: block;" transform="matrix(1,-0.0000012433954452717444,0.0000012433954452717444,1,47.87498474121094,47.057003021240234)" opacity="1">
                            <g class="like_rotate">
                                <g opacity="1" transform="matrix(1,0,0,1,14.376999855041504,11.416000366210938)">
                                    <path stroke-linecap="butt" stroke-linejoin="miter" fill-opacity="0" stroke-miterlimit="10" stroke="rgb(255,255,255)" stroke-opacity="1" stroke-width="2" d=" M-7.936999797821045,9.531000137329102 C-7.936999797821045,9.531000137329102 3.378000020980835,9.531000137329102 3.378000020980835,9.531000137329102 C3.815999984741211,9.531000137329102 4.209000110626221,9.258999824523926 4.360000133514404,8.847000122070312 C4.360000133514404,8.847000122070312 7.501999855041504,0.36000001430511475 7.501999855041504,0.36000001430511475 C8.020000457763672,-1.0360000133514404 6.986000061035156,-2.5199999809265137 5.497000217437744,-2.5199999809265137 C5.497000217437744,-2.5199999809265137 -0.5669999718666077,-2.5199999809265137 -0.5669999718666077,-2.5199999809265137 C-0.6399999856948853,-2.5199999809265137 -0.6859999895095825,-2.5969998836517334 -0.6499999761581421,-2.6600000858306885 C-0.36800000071525574,-3.1679999828338623 0.6269999742507935,-4.922999858856201 0.8870000243186951,-5.764999866485596 C1.309000015258789,-7.13100004196167 0.847000002861023,-8.715999603271484 -1.4539999961853027,-9.519000053405762 C-1.4759999513626099,-9.526000022888184 -1.4989999532699585,-9.527000427246094 -1.5180000066757202,-9.519000053405762 C-1.5299999713897705,-9.513999938964844 -1.5410000085830688,-9.505999565124512 -1.5490000247955322,-9.494000434875488 C-1.7309999465942383,-9.234999656677246 -2.6489999294281006,-7.934000015258789 -3.6419999599456787,-6.52400016784668 C-4.795000076293945,-4.888000011444092 -6.050000190734863,-3.1059999465942383 -6.380000114440918,-2.638000011444092 C-6.434000015258789,-2.562000036239624 -6.519000053405762,-2.5199999809265137 -6.611000061035156,-2.5199999809265137 C-6.611000061035156,-2.5199999809265137 -7.938000202178955,-2.5199999809265137 -7.938000202178955,-2.5199999809265137 C-7.982999801635742,-2.5199999809265137 -8.020000457763672,-2.4839999675750732 -8.020000457763672,-2.437999963760376 C-8.020000457763672,-2.437999963760376 -8.020000457763672,9.447999954223633 -8.020000457763672,9.447999954223633 C-8.020000457763672,9.494000434875488 -7.982999801635742,9.531000137329102 -7.936999797821045,9.531000137329102z"></path>
                                    <path fill="rgb(255,255,255)" fill-opacity="1" d=" M-7.936999797821045,9.531000137329102 C-7.936999797821045,9.531000137329102 3.378000020980835,9.531000137329102 3.378000020980835,9.531000137329102 C3.815999984741211,9.531000137329102 4.209000110626221,9.258999824523926 4.360000133514404,8.847000122070312 C4.360000133514404,8.847000122070312 7.501999855041504,0.36000001430511475 7.501999855041504,0.36000001430511475 C8.020000457763672,-1.0360000133514404 6.986000061035156,-2.5199999809265137 5.497000217437744,-2.5199999809265137 C5.497000217437744,-2.5199999809265137 -0.5669999718666077,-2.5199999809265137 -0.5669999718666077,-2.5199999809265137 C-0.6399999856948853,-2.5199999809265137 -0.6859999895095825,-2.5969998836517334 -0.6499999761581421,-2.6600000858306885 C-0.36800000071525574,-3.1679999828338623 0.6269999742507935,-4.922999858856201 0.8870000243186951,-5.764999866485596 C1.309000015258789,-7.13100004196167 0.847000002861023,-8.715999603271484 -1.4539999961853027,-9.519000053405762 C-1.4759999513626099,-9.526000022888184 -1.4989999532699585,-9.527000427246094 -1.5180000066757202,-9.519000053405762 C-1.5299999713897705,-9.513999938964844 -1.5410000085830688,-9.505999565124512 -1.5490000247955322,-9.494000434875488 C-1.7309999465942383,-9.234999656677246 -2.6489999294281006,-7.934000015258789 -3.6419999599456787,-6.52400016784668 C-4.795000076293945,-4.888000011444092 -6.050000190734863,-3.1059999465942383 -6.380000114440918,-2.638000011444092 C-6.434000015258789,-2.562000036239624 -6.519000053405762,-2.5199999809265137 -6.611000061035156,-2.5199999809265137 C-6.611000061035156,-2.5199999809265137 -7.938000202178955,-2.5199999809265137 -7.938000202178955,-2.5199999809265137 C-7.982999801635742,-2.5199999809265137 -8.020000457763672,-2.4839999675750732 -8.020000457763672,-2.437999963760376 C-8.020000457763672,-2.437999963760376 -8.020000457763672,9.447999954223633 -8.020000457763672,9.447999954223633 C-8.020000457763672,9.494000434875488 -7.982999801635742,9.531000137329102 -7.936999797821045,9.531000137329102z"></path>
                                </g>
                                <g opacity="1" transform="matrix(1,0,0,1,2.694000005722046,14.967000007629395)">
                                    <path fill="rgb(255,255,255)" fill-opacity="1" d=" M0.5019999742507935,7.0269999504089355 C0.5019999742507935,7.0269999504089355 -0.5019999742507935,7.0269999504089355 -0.5019999742507935,7.0269999504089355 C-0.7789999842643738,7.0269999504089355 -1.003999948501587,6.802000045776367 -1.003999948501587,6.525000095367432 C-1.003999948501587,6.525000095367432 -1.003999948501587,-6.525000095367432 -1.003999948501587,-6.525000095367432 C-1.003999948501587,-6.802000045776367 -0.7789999842643738,-7.0269999504089355 -0.5019999742507935,-7.0269999504089355 C-0.5019999742507935,-7.0269999504089355 0.5019999742507935,-7.0269999504089355 0.5019999742507935,-7.0269999504089355 C0.7789999842643738,-7.0269999504089355 1.003999948501587,-6.802000045776367 1.003999948501587,-6.525000095367432 C1.003999948501587,-6.525000095367432 1.003999948501587,6.525000095367432 1.003999948501587,6.525000095367432 C1.003999948501587,6.802000045776367 0.7789999842643738,7.0269999504089355 0.5019999742507935,7.0269999504089355z"></path>
                                </g>
                            </g>
                        </g>
                    </g>
                 </svg>
                 <span>赞&nbsp;<span id="like_label" class="like_label"></span></span>
                 </button><div class="mt20 text-center article__reward-info">
                        <span class="mr10">如果喜欢我的文章,觉得对你有帮助,请随意赞赏!</span>
                       </div>
                     </div><!--support-author-->             <!--/文章的页脚部件：打赏和其他信息的输出-->
         </div>
        </article>
       </div>
       <!--上一篇&下一篇-->
       <nav class="m-t-lg m-b-lg">
        <ul class="pager">
        <li class="next"> <a class="box-shadow-wrap-normal" href="https://www.ioiox.com/archives/109.html" title="腾讯云对象存储 COSFS 工具安装配置与使用命令" data-toggle="tooltip"> 
下一篇 </a></li>   <li class="previous"> <a class="box-shadow-wrap-normal" href="https://www.ioiox.com/archives/111.html" title="OpenWrt 及 ROS 配置防火墙使内网用户直接访问光猫" data-toggle="tooltip"> 上一篇 </a></li>
        </ul>
       </nav>
       <!--评论-->
        
    
    
    <div id="comments">

                    <!--评论列表-->
            <div id="post-comment-list" class="skt-loading"><h4 class="comments-title m-t-lg m-b">1 条评论</h4><nav class="loading-nav text-center m-t-lg m-b-lg hide">
<p class="infinite-scroll-request"><i class="animate-spin fontello fontello-refresh"></i>Loading...</p>
</nav><ol class="comment-list">
        <!--自定义评论代码结构-->

        <li id="pingback-2758" class="comment-body comment-parent comment-odd">
            <div id="div-pingback-2758" class="comment-body">

                <a class="pull-left thumb-sm comment-avatar" rel="nofollow">
                    <img nogallery src="https://gravatar.ioiox.net/avatar/d41d8cd98f00b204e9800998ecf8427e?s=65&r=G&d=" class="img-40px photo img-square normal-shadow">                    
                </a>
                <div class="m-b m-l-xxl">
                    <div class="comment-meta">
            <span class="comment-author vcard">
              <b class="fn"><a href="https://www.vlinux.cn/675.html"target="_blank" rel="external nofollow" class="no-external-link">腾讯云对象存储COSCMD工具安装配置与使用命令详解 R11; 运维之境</a></b>
                                <a data-coid="2758" class="post-comment-star text-muted star_talk"><i class="glyphicon glyphicon-heart-empty"></i>&nbsp;<span class="star_count"></span></a>
                              </span>
                        <div class="comment-metadata">
                            <a href="#pingback-2758"><time class="format_time text-muted text-xs block m-t-xs" pubdate="pubdate" datetime="2021-04-04T18:41:19+08:00">April 4th, 2021 at 06:41 pm</time></a>
                        </div>
                    </div>
                    <!--回复内容-->
                    <div class="comment-content m-t-sm">
                        <span class="comment-author-at"><b></b></span><div class="comment-content-true">
                            <p>[...]<a href="https://www.ioiox.com/archives/110.html">https://www.ioiox.com/archives/110.html</a>[...]</p>                        </div>
                    </div>
                    <!--回复按钮-->
                    <div class="comment-reply m-t-sm">
                        <a href="https://www.ioiox.com/archives/110.html/comment-page-1?replyTo=2758#respond-post-1338" rel="nofollow" onclick="return TypechoComment.reply('pingback-2758', 2758);">回复</a>                    </div>
                </div>

            </div>
            <!-- 单条评论者信息及内容 -->
             <!-- 是否嵌套评论判断结束 -->
        </li><!--匹配`自定义评论的代码结构`下面的li标签-->
    </ol><nav id="comment-navigation" class="text-center m-t-lg m-b-lg" role="navigation"></nav><script type="text/javascript" id='outputCommentJS'>
(function () {
    window.TypechoComment = {
        dom : function (id) {
            return document.getElementById(id);
        },
    
        create : function (tag, attr) {
            var el = document.createElement(tag);
        
            for (var key in attr) {
                el.setAttribute(key, attr[key]);
            }
        
            return el;
        },

        reply : function (cid, coid) {
            var comment = this.dom(cid), parent = comment.parentNode,
                response = this.dom('respond-post-1338'), input = this.dom('comment-parent'),
                form = 'form' == response.tagName ? response : response.getElementsByTagName('form')[0],
                textarea = response.getElementsByTagName('textarea')[0];

            if (null == input) {
                input = this.create('input', {
                    'type' : 'hidden',
                    'name' : 'parent',
                    'id'   : 'comment-parent'
                });

                form.appendChild(input);
            }

            input.setAttribute('value', coid);

            if (null == this.dom('comment-form-place-holder')) {
                var holder = this.create('div', {
                    'id' : 'comment-form-place-holder'
                });

                response.parentNode.insertBefore(holder, response);
            }

            comment.appendChild(response);
            this.dom('cancel-comment-reply-link').style.display = '';

            if (null != textarea && 'text' == textarea.name) {
                textarea.focus();
            }

            return false;
        },

        cancelReply : function () {
            var response = this.dom('respond-post-1338'),
            holder = this.dom('comment-form-place-holder'), input = this.dom('comment-parent');

            if (null != input) {
                input.parentNode.removeChild(input);
            }

            if (null == holder) {
                return true;
            }

            this.dom('cancel-comment-reply-link').style.display = 'none';
            holder.parentNode.insertBefore(response, holder);
            return false;
        }
    };
})();
</script>
<script type="text/javascript">
var registCommentEvent = function() {
    var event = document.addEventListener ? {
        add: 'addEventListener',
        focus: 'focus',
        load: 'DOMContentLoaded'
    } : {
        add: 'attachEvent',
        focus: 'onfocus',
        load: 'onload'
    };
    
    var r = document.getElementById('respond-post-1338');
    if (null != r) {
        var forms = r.getElementsByTagName('form');
        if (forms.length > 0) {
            var f = forms[0], textarea = f.getElementsByTagName('textarea')[0], added = false;
            var submitButton = f.querySelector('button[type="submit"]');
            if (null != textarea && 'text' == textarea.name) {
                var referSet =  function () {
                    if (!added) {
//                        console.log('commentjs');
                        const child = f.querySelector('input[name="_"]');
                        const child2 = f.querySelector('input[name="checkReferer"]');
                        if (child!=null){
                            f.removeChild(child);                        
                        } 
                        if (child2!=null){
                            f.removeChild(child2);                        
                        } 
                        var input = document.createElement('input');
                        input.type = 'hidden';
                        input.name = '_';
                            input.value = (function () {
    var _SXcB0Cr = //'tc'
'f6a'+'091'//'a'
+//'IaQ'
'767'+//'Xj'
'07a'+/* '1Ol'//'1Ol' */''+//'w9'
'e95'+//'3N'
'b'+//'N2K'
'1'+'ee1'//'x'
+//'T'
'3'+''///*'4'*/'4'
+//'N4'
'4'+''///*'0'*/'0'
+'247'//'li'
+//'wfk'
'ecd'+'8d'//'IZm'
+'20'//'IFi'
, _5AXACQq = [];
    
    for (var i = 0; i < _5AXACQq.length; i ++) {
        _SXcB0Cr = _SXcB0Cr.substring(0, _5AXACQq[i][0]) + _SXcB0Cr.substring(_5AXACQq[i][1]);
    }

    return _SXcB0Cr;
})();
                    
                        f.appendChild(input);
                        
                        input = document.createElement('input');
                        input.type = 'hidden';
                        input.name = 'checkReferer';
                        input.value = 'false';
                        
                        f.appendChild(input);
                        

                        added = true;
                    }
                };//end of reset
                referSet();
            }
        }
    }
};

$(function(){
    registCommentEvent();
});
</script></div>        
        <!--如果允许评论，会出现评论框和个人信息的填写-->
                                    <div id="respond-post-1338" class="respond comment-respond no-borders">

                    <h4 id="reply-title" class="comment-reply-title m-t-lg m-b-none">发表评论                        <small class="cancel-comment-reply">
                            <a id="cancel-comment-reply-link" href="https://www.ioiox.com/archives/110.html#respond-post-1338" rel="nofollow" style="display:none" onclick="return TypechoComment.cancelReply();">取消回复</a>                        </small>
                        <div class="text-muted m-t-xs" style="font-size: 13px;line-height: 18px;">
                            <i style="vertical-align: -2px;width:14px;height: 14px" data-feather="alert-circle"></i>
                            使用cookie技术保留您的个人信息以便您下次快速评论，继续评论表示您已同意该条款                        </div>
                    </h4>
                    <form id="comment_form" method="post" action="https://www.ioiox.com/archives/110.html/comment"  class="comment-form" role="form">
                        <input type="hidden" name="receiveMail" id="receiveMail" value="yes" />
                        <div class="comment-form-comment form-group">
                            <label class="padder-v-sm" for="comment">评论                                <span class="required text-danger">*</span></label>
                            <textarea id="comment" class="textarea form-control OwO-textarea" name="text" rows="5" placeholder="说点什么吧……" onkeydown="if(event.ctrlKey&&event.keyCode==13){document.getElementById('submit').click();return false};"></textarea>
                            <div class="OwO padder-v-sm"></div>
                                                        <div class="secret_comment" id="secret_comment" data-toggle="tooltip"
                            data-original-title="开启该功能，您的评论仅作者和评论双方可见">
                                <label class="secret_comment_label control-label">私密评论</label>
                                <div class="secret_comment_check">
                                    <label class="i-switch i-switch-sm bg-info m-b-ss m-r">
                                        <input type="checkbox" id="secret_comment_checkbox">
                                        <i></i>
                                    </label>
                                </div>
                            </div>
                                                    </div>
                        <!--判断是否登录-->
                                                                            <div id="author_info" class="row row-sm">
                                                                <div class="comment-form-author form-group col-sm-6 col-md-4">
                                    <label for="author">名称                                        <span class="required text-danger">*</span></label>
                                    <div>
                                                                                <img class="author-avatar" src="https://gravatar.ioiox.net/avatar/d41d8cd98f00b204e9800998ecf8427e?s=65&r=G&d=" nogallery/>
                                        <input id="author" class="form-control" name="author" type="text" value="" maxlength="245" placeholder="姓名或昵称">
                                                                                <div class="random_user_name shake-constant">🎲</div>
                                                                            </div>
                                </div>

                                <div class="comment-form-email form-group col-sm-6 col-md-4">
                                    <label for="email">邮箱                                                                                <span class="required text-danger">*</span>
                                                                            </label>
                                    <input type="text" name="mail" id="mail" class="form-control" placeholder="邮箱 (必填,将保密)" value="" />
                                </div>

                                <div class="comment-form-url form-group col-sm-12 col-md-4">
                                    <label for="url">地址                                                                            </label>
                                    <input id="url" class="form-control" name="url" type="url" value="" maxlength="200" placeholder="网站或博客"></div>
                            </div>
                                                        <!--提交按钮-->
                            <div class="form-group">
                                <button type="submit" name="submit" id="submit" class="submit btn-rounded box-shadow-wrap-lg btn-gd-primary padder-lg">
                                    <span>发表评论</span>
                                    <span class="text-active">提交中...</span>
                                </button>
                                <i class="animate-spin fontello fontello-spinner hide" id="spin"></i>
                                <input type="hidden" name="comment_post_ID" id="comment_post_ID">
                                <input type="hidden" name="comment_parent" id="comment_parent">
                            </div>
                    </form>
                </div>
                    
            </div>


      </div>
         <div class="resize-pane">
        <div id="trigger_right_content" class="trigger_content"><div class="trigger_drag_content"></div></div>
        <div id="trigger_right_button" data-placement="left" data-toggle="tooltip" data-original-title="点击展开右侧边栏" class="normal-widget resize-pane-trigger box-shadow-wrap-lg"><i data-feather="sidebar"></i></div>
    </div>     </div>
     <!--文章右侧边栏开始-->
             <aside id="rightAside" class="asideBar col w-md bg-white-only bg-auto no-border-xs" role="complementary">
     <div id="sidebar">
               <section id="right_first_section" class="widget widget_tabs clear">
       <div class="nav-tabs-alt no-js-hide new-nav-tab-wrap">
        <ul class="nav nav-tabs nav-justified box-shadow-wrap-normal tablist new-nav-tab" role="tablist">
            <li  data-index="0" class="active" role="presentation"> <a  data-target="#widget-tabs-4-hots" role="tab"
                                                                   aria-controls="widget-tabs-4-hots" aria-expanded="true" data-toggle="tab"><div class="sidebar-icon" data-toggle="tooltip" title="热门文章" data-container="body"><i data-feather="thumbs-up"></i><span class="sr-only">热门文章</span></div> </a></li>
                            <li role="presentation" data-index="1"> <a data-target="#widget-tabs-4-comments" role="tab" aria-controls="widget-tabs-4-comments" aria-expanded="false" data-toggle="tab"><div data-toggle="tooltip" title="最新评论" data-container="body" class="sidebar-icon"><i  data-feather="message-square"></i><span class="sr-only">最新评论</span></div>  </a></li>
                        <li data-index="2" role="presentation"> <a data-target="#widget-tabs-4-random" role="tab" aria-controls="widget-tabs-4-random" aria-expanded="false" data-toggle="tab"> <div data-toggle="tooltip" title="随机文章" data-container="body" class="sidebar-icon"><i data-feather="gift"></i><span class="sr-only">随机文章</span></div>
             </a></li>
            <span class="navs-slider-bar"></span>
        </ul>
       </div>
       <div class="tab-content new-nav-tab-content">
       <!--热门文章-->
        <div id="widget-tabs-4-hots" class="tab-pane  fade in wrapper-md active" role="tabpanel">
<!--         <h5 class="widget-title m-t-none text-md">--><!--</h5>-->
         <ul class="list-group no-bg no-borders pull-in m-b-none">
          <li class="list-group-item">
                <a href="https://www.ioiox.com/archives/26.html" class="pull-left thumb-sm m-r"></a>
                <div class="clear">
                    <h4 class="h5 l-h text-second text-ellipsis"> <a href="https://www.ioiox.com/archives/26.html" title="群晖NAS使用Docker安装配置frpc内网穿透教程"> 群晖NAS使用Docker安装配置frpc内网穿透教程 </a></h4>
                    <small class="text-muted post-head-icon text-second"><span class="meta-date"> <i class="fontello fontello-eye" aria-hidden="true"></i> <span class="sr-only">浏览次数:</span> <span class="meta-value">662523</span>
                    </span>
              </small></div></li><li class="list-group-item">
                <a href="https://www.ioiox.com/archives/94.html" class="pull-left thumb-sm m-r"></a>
                <div class="clear">
                    <h4 class="h5 l-h text-second text-ellipsis"> <a href="https://www.ioiox.com/archives/94.html" title="本站提供免费 RSS 和 RSSHub 服务"> 本站提供免费 RSS 和 RSSHub 服务 </a></h4>
                    <small class="text-muted post-head-icon text-second"><span class="meta-date"> <i class="fontello fontello-eye" aria-hidden="true"></i> <span class="sr-only">浏览次数:</span> <span class="meta-value">219940</span>
                    </span>
              </small></div></li><li class="list-group-item">
                <a href="https://www.ioiox.com/archives/6.html" class="pull-left thumb-sm m-r"></a>
                <div class="clear">
                    <h4 class="h5 l-h text-second text-ellipsis"> <a href="https://www.ioiox.com/archives/6.html" title="群晖NAS安装配置免费frp内网穿透教程"> 群晖NAS安装配置免费frp内网穿透教程 </a></h4>
                    <small class="text-muted post-head-icon text-second"><span class="meta-date"> <i class="fontello fontello-eye" aria-hidden="true"></i> <span class="sr-only">浏览次数:</span> <span class="meta-value">197852</span>
                    </span>
              </small></div></li><li class="list-group-item">
                <a href="https://www.ioiox.com/archives/89.html" class="pull-left thumb-sm m-r"></a>
                <div class="clear">
                    <h4 class="h5 l-h text-second text-ellipsis"> <a href="https://www.ioiox.com/archives/89.html" title="OpenWRT 路由器 OpenConnect VPN 详细图文教程 - 基础配置篇"> OpenWRT 路由器 OpenConnect VPN 详细图文教程 - 基础配置篇 </a></h4>
                    <small class="text-muted post-head-icon text-second"><span class="meta-date"> <i class="fontello fontello-eye" aria-hidden="true"></i> <span class="sr-only">浏览次数:</span> <span class="meta-value">155508</span>
                    </span>
              </small></div></li><li class="list-group-item">
                <a href="https://www.ioiox.com/archives/143.html" class="pull-left thumb-sm m-r"></a>
                <div class="clear">
                    <h4 class="h5 l-h text-second text-ellipsis"> <a href="https://www.ioiox.com/archives/143.html" title="OpenWRT 配置 WireGuard 服务端及客户端配置教程"> OpenWRT 配置 WireGuard 服务端及客户端配置教程 </a></h4>
                    <small class="text-muted post-head-icon text-second"><span class="meta-date"> <i class="fontello fontello-eye" aria-hidden="true"></i> <span class="sr-only">浏览次数:</span> <span class="meta-value">105982</span>
                    </span>
              </small></div></li>         </ul>
        </div>
                   <!--最新评论-->
        <div id="widget-tabs-4-comments" class="tab-pane fade wrapper-md no-js-show" role="tabpanel">
<!--         <h5 class="widget-title m-t-none text-md">--><!--</h5>-->
         <ul class="list-group no-borders pull-in auto m-b-none no-bg">
                              <li class="list-group-item">

              <a href="https://www.ioiox.com/archives/52.html/comment-page-1#comment-5041" class="pull-left thumb-sm avatar m-r">
                                </a>
              <a href="https://www.ioiox.com/archives/52.html/comment-page-1#comment-5041" class="text-muted">
                  <!--<i class="iconfont icon-comments-o text-muted pull-right m-t-sm text-sm" title="" aria-hidden="true" data-toggle="tooltip" data-placement="auto left"></i>
                  <span class="sr-only"></span>-->
              </a>
              <div class="clear">
                  <div class="text-ellipsis">
                      <a href="https://www.ioiox.com/archives/52.html/comment-page-1#comment-5041" title="XJH"> XJH </a>
                  </div>
                  <small class="text-muted">
                      <span>
                          老哥您好，frp突然不好用，连接时经常会提示login to ...                      </span>
                  </small>
              </div>
          </li>
                    <li class="list-group-item">

              <a href="https://www.ioiox.com/archives/96.html/comment-page-1#comment-5039" class="pull-left thumb-sm avatar m-r">
                                </a>
              <a href="https://www.ioiox.com/archives/96.html/comment-page-1#comment-5039" class="text-muted">
                  <!--<i class="iconfont icon-comments-o text-muted pull-right m-t-sm text-sm" title="" aria-hidden="true" data-toggle="tooltip" data-placement="auto left"></i>
                  <span class="sr-only"></span>-->
              </a>
              <div class="clear">
                  <div class="text-ellipsis">
                      <a href="https://www.ioiox.com/archives/96.html/comment-page-1#comment-5039" title="娃娃"> 娃娃 </a>
                  </div>
                  <small class="text-muted">
                      <span>
                          是否能使用dhcp功能呢？路由器关闭dhcp，adguard ...                      </span>
                  </small>
              </div>
          </li>
                    <li class="list-group-item">

              <a href="https://www.ioiox.com/archives/25.html/comment-page-1#comment-5038" class="pull-left thumb-sm avatar m-r">
                                </a>
              <a href="https://www.ioiox.com/archives/25.html/comment-page-1#comment-5038" class="text-muted">
                  <!--<i class="iconfont icon-comments-o text-muted pull-right m-t-sm text-sm" title="" aria-hidden="true" data-toggle="tooltip" data-placement="auto left"></i>
                  <span class="sr-only"></span>-->
              </a>
              <div class="clear">
                  <div class="text-ellipsis">
                      <a href="https://www.ioiox.com/archives/25.html/comment-page-1#comment-5038" title="sxfd"> sxfd </a>
                  </div>
                  <small class="text-muted">
                      <span>
                          我这个安装的过程中一点击网络，它整个屏幕就拉伸了，怎么办？                      </span>
                  </small>
              </div>
          </li>
                    <li class="list-group-item">

              <a href="https://www.ioiox.com/archives/28.html/comment-page-1#comment-5036" class="pull-left thumb-sm avatar m-r">
                                </a>
              <a href="https://www.ioiox.com/archives/28.html/comment-page-1#comment-5036" class="text-muted">
                  <!--<i class="iconfont icon-comments-o text-muted pull-right m-t-sm text-sm" title="" aria-hidden="true" data-toggle="tooltip" data-placement="auto left"></i>
                  <span class="sr-only"></span>-->
              </a>
              <div class="clear">
                  <div class="text-ellipsis">
                      <a href="https://www.ioiox.com/archives/28.html/comment-page-1#comment-5036" title="klcdm"> klcdm </a>
                  </div>
                  <small class="text-muted">
                      <span>
                          该评论仅登录用户及评论双方可见                      </span>
                  </small>
              </div>
          </li>
                    <li class="list-group-item">

              <a href="https://www.ioiox.com/archives/169.html/comment-page-1#comment-5034" class="pull-left thumb-sm avatar m-r">
                                </a>
              <a href="https://www.ioiox.com/archives/169.html/comment-page-1#comment-5034" class="text-muted">
                  <!--<i class="iconfont icon-comments-o text-muted pull-right m-t-sm text-sm" title="" aria-hidden="true" data-toggle="tooltip" data-placement="auto left"></i>
                  <span class="sr-only"></span>-->
              </a>
              <div class="clear">
                  <div class="text-ellipsis">
                      <a href="https://www.ioiox.com/archives/169.html/comment-page-1#comment-5034" title="挺胸的道士"> 挺胸的道士 </a>
                  </div>
                  <small class="text-muted">
                      <span>
                          因為我以為外面那個大卡套沒用的就丟掉了，留下了芯片，結果插卡進...                      </span>
                  </small>
              </div>
          </li>
                   </ul>
        </div>
                   <!--随机文章-->
        <div id="widget-tabs-4-random" class="tab-pane fade wrapper-md no-js-show" role="tabpanel">
<!--            <h5 class="widget-title m-t-none text-md">--><!--</h5>-->
            <ul class="list-group no-bg no-borders pull-in m-b-none">
            <li class="list-group-item">
                <a href="https://www.ioiox.com/archives/6.html" class="pull-left thumb-sm m-r"></a>
                <div class="clear">
                    <h4 class="h5 l-h text-second text-ellipsis"> <a href="https://www.ioiox.com/archives/6.html" title="群晖NAS安装配置免费frp内网穿透教程"> 群晖NAS安装配置免费frp内网穿透教程 </a></h4>
                    <small class="text-muted post-head-icon"><span class="meta-date"> <i class="fontello fontello-eye" aria-hidden="true"></i> <span class="sr-only">浏览次数:</span> <span class="meta-value">197852</span>
                    </span>
              </small></div></li><li class="list-group-item">
                <a href="https://www.ioiox.com/archives/141.html" class="pull-left thumb-sm m-r"></a>
                <div class="clear">
                    <h4 class="h5 l-h text-second text-ellipsis"> <a href="https://www.ioiox.com/archives/141.html" title="做了个在线申请泛域名证书的网站,欢迎使用."> 做了个在线申请泛域名证书的网站,欢迎使用. </a></h4>
                    <small class="text-muted post-head-icon"><span class="meta-date"> <i class="fontello fontello-eye" aria-hidden="true"></i> <span class="sr-only">浏览次数:</span> <span class="meta-value">17158</span>
                    </span>
              </small></div></li><li class="list-group-item">
                <a href="https://www.ioiox.com/archives/131.html" class="pull-left thumb-sm m-r"></a>
                <div class="clear">
                    <h4 class="h5 l-h text-second text-ellipsis"> <a href="https://www.ioiox.com/archives/131.html" title="轻量级高性能 HTTP/HTTPS SOCKS5 代理软件 goproxy docker 部署教程"> 轻量级高性能 HTTP/HTTPS SOCKS5 代理软件 goproxy docker 部署教程 </a></h4>
                    <small class="text-muted post-head-icon"><span class="meta-date"> <i class="fontello fontello-eye" aria-hidden="true"></i> <span class="sr-only">浏览次数:</span> <span class="meta-value">16342</span>
                    </span>
              </small></div></li><li class="list-group-item">
                <a href="https://www.ioiox.com/archives/80.html" class="pull-left thumb-sm m-r"></a>
                <div class="clear">
                    <h4 class="h5 l-h text-second text-ellipsis"> <a href="https://www.ioiox.com/archives/80.html" title="docker compose 部署迁移 Chevereto 图床程序教程"> docker compose 部署迁移 Chevereto 图床程序教程 </a></h4>
                    <small class="text-muted post-head-icon"><span class="meta-date"> <i class="fontello fontello-eye" aria-hidden="true"></i> <span class="sr-only">浏览次数:</span> <span class="meta-value">13274</span>
                    </span>
              </small></div></li><li class="list-group-item">
                <a href="https://www.ioiox.com/archives/114.html" class="pull-left thumb-sm m-r"></a>
                <div class="clear">
                    <h4 class="h5 l-h text-second text-ellipsis"> <a href="https://www.ioiox.com/archives/114.html" title="群晖 Synology DSM 7.0 测试版已正式发布 附下载地址"> 群晖 Synology DSM 7.0 测试版已正式发布 附下载地址 </a></h4>
                    <small class="text-muted post-head-icon"><span class="meta-date"> <i class="fontello fontello-eye" aria-hidden="true"></i> <span class="sr-only">浏览次数:</span> <span class="meta-value">31791</span>
                    </span>
              </small></div></li>            </ul>
        </div>
       </div>
      </section>
               <!--博客信息-->
               <section id="blog_info" class="widget widget_categories wrapper-md padder-v-none clear">
       <h5 class="widget-title m-t-none">博客信息</h5>
       <ul class="list-group box-shadow-wrap-normal">
                      <li class="list-group-item text-second"><span class="blog-info-icons"> <i data-feather="award"></i></span> <span
                       class="badge
           pull-right">173</span>文章数目</li>
                      <li class="list-group-item text-second"> <span class="blog-info-icons"> <i data-feather="message-circle"></i></span>
               <span class="badge
           pull-right">4622</span>评论数目</li>
                      <li class="list-group-item text-second"><span class="blog-info-icons"> <i data-feather="calendar"></i></span>
               <span class="badge
           pull-right">5年96天</span>运行天数</li>
           <li class="list-group-item text-second"><span class="blog-info-icons"> <i data-feather="activity"></i></span> <span
                       class="badge
           pull-right">4 个月前</span>最后活动</li>
       </ul>
      </section>
                        <!--广告位置-->
         <section id="a_d_sidebar" class="widget widget_categories wrapper-md clear">
             <h5 class="widget-title m-t-none">广告</h5>
            <a
  href="https://go.ssrdog.com/?code=gBXmmXyG"
  target="_blank"
  style="color: #ff5733"
  >晚高峰稳定 4K 的 IPLC 机场 解锁各流媒体 支持 ChatGPT.</a
>
<a href="https://go.ssrdog.com/?code=gBXmmXyG" target="_blank">
  <img
    src="https://i.ioiox.com/2024/01/18/1705546726956CxSjol.jpg"
    alt="晚高峰稳定 4K 的 IPLC 机场 解锁各流媒体 支持 ChatGPT."
  />
</a>
<a
  href="https://www.ioiox.com/archives/171.html"
  target="_blank"
  style="color: #ff5733"
  >RedteaGO - 最划算的大陆漫游 eSim 流量卡，原生境外 IP，注册就送 3 刀。</a
>
<br />
<a href="https://www.ioiox.com/archives/171.html" target="_blank">
  <img
    src="https://i.ioiox.com/2024/01/18/1705546340734mZWe4Z.jpg"
    alt="RedteaGO - 最划算的大陆漫游 eSim 流量卡，原生境外 IP，注册就送 3 刀。"
  />
</a>         </section>
                  <!--非文章页面-->
                <!--文章页面-->
          <section id="tag_cloud-post" class="widget widget_tag_cloud wrapper-md clear">
              <h5 class="widget-title m-t-none">文章标签</h5>
              <div class="tags l-h-2x panel wrapper-sm padder-v-ssm">
                  <a href="https://www.ioiox.com/tag/%E8%85%BE%E8%AE%AF%E4%BA%91/">腾讯云</a> <a href="https://www.ioiox.com/tag/COS/">COS</a> <a href="https://www.ioiox.com/tag/%E5%AF%B9%E8%B1%A1%E5%AD%98%E5%82%A8/">对象存储</a> <a href="https://www.ioiox.com/tag/COSCMD/">COSCMD</a>              </div>
          </section>
          <div id="tag_toc_body" class="tag_toc_body">
              <section id="tag_toc" class="widget widget_categories wrapper-md clear">
                  <h5 class="widget-title m-t-none">文章目录</h5>
                  <div class="tags l-h-2x box-shadow-wrap-normal">
                      <div id="toc" class="small-scroll-bar overflow-y-auto"></div>
                  </div>
              </section>
          </div>

        </div>
     </aside>
       <!--文章右侧边栏结束-->
    </div>
   </main>


    
<div id="morphing-content" class="hidden read_mode_article">
        <div class="page">
            <h1 class="title">腾讯云对象存储 COSCMD 工具安装配置与使用命令 </h1>
            <div class="metadata singleline"><a href="#" rel="author" class="byline">Stille</a>&nbsp;•&nbsp;<span class="delimiter"></span><time class="date">2020 年 07 月 08 日</time></div>     
            <textarea id="morphing-content-real_origin_text">&lt;h2&gt;前言&lt;/h2&gt;&lt;p&gt;COSCMD 工具是一款腾讯云 COS 的命令行操作工具,能方便的在 Linux 服务器上管理对象存储 COS 中的桶文件,支持上传文件,文件夹,下载文件,文件夹,以及删除功能.配合更详细的参数例如 md5 比对,跳过,删除等可以很方便的配置定时备份服务器上的文件到 COS 中.本文将简单介绍在 Linux 系统中的安装,配置和常规上传下载命令,更详细的用法请参考下文中的相关参考链接.&lt;/p&gt;&lt;p&gt;&lt;div class=&quot;tip inlineBlock success&quot;&gt;本文为&lt;a href=&quot;https://www.ioiox.com/stille.html&quot; target=&quot;_blank&quot;&gt; Stille &lt;/a&gt;原创文章.经实践,测试,整理发布.如需转载请联系作者获得授权,并注明转载地址.&lt;/div&gt;&lt;hr&gt;&lt;h2&gt;安装&lt;/h2&gt;&lt;h3&gt;环境依赖&lt;/h3&gt;&lt;ul&gt;&lt;li&gt;Python 2.7/3.5/3.6&lt;/li&gt;&lt;li&gt;最新版本的 pip&lt;/li&gt;&lt;/ul&gt;&lt;h3&gt;安装命令&lt;/h3&gt;&lt;pre&gt;&lt;code class=&quot;lang-bash&quot;&gt;yum -y install python-pip
python -m pip install --upgrade pip    
pip install -I requests
pip install coscmd&lt;/code&gt;&lt;/pre&gt;&lt;p&gt;&amp;nbsp;&amp;nbsp;&lt;br&gt;&lt;img src=&quot;https://www.ioiox.com/usr/uploads/2020/04/4267100629.png&quot; alt=&quot;&quot; title=&quot;&quot; style=&quot;&quot;&gt;&lt;/p&gt;&lt;h2&gt;配置&lt;/h2&gt;&lt;h3&gt;获取存储痛信息&lt;/h3&gt;&lt;h4&gt;登录腾讯云 - 控制台 - 对象存储 - 存储桶获取相关信息&lt;/h4&gt;&lt;ul&gt;&lt;li&gt;BucketName-APPID : &lt;code&gt;test-1250000000&lt;/code&gt; 为存储桶名称&lt;/li&gt;&lt;li&gt;区域地址 : &lt;code&gt;https://cos.ap-shanghai.myqcloud.com&lt;/code&gt; 存储桶所在的区域域名.&lt;/li&gt;&lt;/ul&gt;&lt;h4&gt;登录腾讯云 - 控制台 - 访问管理&lt;/h4&gt;&lt;p&gt;创建子账号并赋予 COS 相关权限,生成&lt;code&gt;SecretId&lt;/code&gt;和&lt;code&gt;SecretKey&lt;/code&gt;.&lt;/p&gt;&lt;ul&gt;&lt;li&gt;SecretId : XXXXXX&lt;/li&gt;&lt;li&gt;SecretKey : XXXXXX&lt;/li&gt;&lt;/ul&gt;&lt;h3&gt;配置密钥&lt;/h3&gt;&lt;pre&gt;&lt;code class=&quot;lang-bash&quot;&gt;coscmd config -a AKIxxxxxxxxxxxxxx -s xxxxxxxxxxxxxxxxx -b test-1250000000 -r ap-shanghai&lt;/code&gt;&lt;/pre&gt;&lt;p&gt;&amp;nbsp;&amp;nbsp;&lt;br&gt;&lt;img src=&quot;https://www.ioiox.com/usr/uploads/2020/04/4267100629.png&quot; alt=&quot;&quot; title=&quot;&quot; style=&quot;&quot;&gt;&lt;/p&gt;&lt;h2&gt;命令&lt;/h2&gt;&lt;h3&gt;参数&lt;/h3&gt;&lt;pre&gt;&lt;code class=&quot;lang-bash&quot;&gt;-f
# 强制跳过提示
-r
# 递归子目录
-s
# 比对 md5
--delete
# 对比并删除文件
--ignore
# 忽略文件或文件夹,支持 *.* 或文件夹路径.&lt;/code&gt;&lt;/pre&gt;&lt;h3&gt;下载文件 / 文件夹&lt;/h3&gt;&lt;pre&gt;&lt;code class=&quot;lang-bash&quot;&gt;coscmd download -f -s /test/test.txt /data/
# 下载文件
coscmd download -rf -s --delete /test /data/
# 下载文件夹
# 结尾含 / 则下载桶中 /test 整个目录至本地 /data 目录之下,路径为 /data/test
# 结尾不含 / 则下载桶中 /test 目录内所有子目录和文件至本地 /data 目录之下&lt;/code&gt;&lt;/pre&gt;&lt;h3&gt;上传文件 / 文件夹&lt;/h3&gt;&lt;pre&gt;&lt;code class=&quot;lang-bash&quot;&gt;coscmd upload -f -s /test/test.txt /data/
# 上传文件
coscmd upload -rf -s --delete /test /data/
# 上传文件夹
# 结尾含 / 则上传本地 /test 整个目录至桶中 /data 目录之下,路径为 /data/test
# 结尾不含 / 则上传本地 /test 目录内所有子目录和文件至桶中 /data 目录之下&lt;/code&gt;&lt;/pre&gt;&lt;hr&gt;&lt;h2&gt;结语&lt;/h2&gt;&lt;p&gt;推荐当服务器也是腾讯云时,可以创建与服务器同区域的对象存储,此时两者为内网传输速度,并且 COS 不计下行流量,搭配 crontab 做定时备份任务非常高效稳定.其他更多相关信息请参考以下链接:&lt;br&gt;&lt;div class=&quot;tip inlineBlock share&quot;&gt;&lt;span class=&quot;external-link&quot;&gt;&lt;a class=&quot;no-external-link&quot; href=&quot;https://cloud.tencent.com/document/product/436/10976&quot; target=&quot;_blank&quot;&gt;&lt;i data-feather=&quot;external-link&quot;&gt;&lt;/i&gt;腾讯云 COSCMD 工具&lt;/a&gt;&lt;/span&gt;&lt;br&gt;&lt;span class=&quot;external-link&quot;&gt;&lt;a class=&quot;no-external-link&quot; href=&quot;https://cloud.tencent.com/document/product/436/30744&quot; target=&quot;_blank&quot;&gt;&lt;i data-feather=&quot;external-link&quot;&gt;&lt;/i&gt;COSCMD 工具类常见问题&lt;/a&gt;&lt;/span&gt;&lt;/div&gt;&lt;hr class=&quot;content-copyright&quot; style=&quot;margin-top:50px&quot; /&gt;&lt;div align=&quot;center&quot;&gt;&lt;p class=&quot;content-copyright&quot;&gt;&lt;div class=&quot;tip inlineBlock success&quot;&gt;

本文为&lt;a class=&quot;content-copyright&quot; href=&quot;https://www.ioiox.com/stille.html&quot;&gt; Stille &lt;/a&gt;原创文章.经实践,测试,整理发布.如需转载请联系作者获得授权,并注明转载地址.&lt;/p&gt;
                    &lt;p align=&quot;left&quot;&gt;本文链接 &lt;a class=&quot;content-copyright&quot; href=&quot;https://www.ioiox.com/archives/110.html&quot;&gt;https://www.ioiox.com/archives/110.html&lt;/a&gt;
&lt;/div&gt;&lt;/p&gt;&lt;/div&gt;</textarea>
<div id="morphing-content-real_origin"></div>
        </div>
    </div>
<!-- footer -->
	</div><!-- /content -->

<!--right panel-->
    <script type="text/template" id="tmpl-customizer">
        <div class="settings panel panel-default setting_body_panel right_panel" aria-hidden="true">
            <button class="rightSettingBtn btn btn-default pos-abt border-radius-half-left"
                    data-toggle="tooltip" data-placement="left" data-original-title="夜/日间模式"
                    data-toggle-class=".settings=active, .settings-icon=animate-spin-span,.tocify-mobile-panel=false">
                  <span class="settings-icon"><i width="13px" height="13px"
                                                 data-feather="settings"></i></span>
            </button>
            <div class="panel-heading">
                <button class="mode-set pull-right btn btn-xs btn-rounded btn-danger " name="reset" data-toggle="tooltip"
                        data-placement="left" data-original-title="恢复默认值" >重置</button>
                夜/日间模式
            </div>
            <div class="setting_body">
                <div class="panel-body">
                    <# for ( var keys = _.keys( data.sections.settings ), i = 0, name; keys.length > i; ++i ) { #>
                    <div<# if ( i !== ( keys.length - 1 ) ) print( ' class="m-b-sm"' ); else print(' id="mode_set" class="mode_set"')
                    #>>
                    <label class="i-switch bg-info pull-right">
                        <input type="checkbox" name="{{ keys[i] }}" <#
                        print( ' value="'+handsome_UI.mode+data
                        .defaults[keys[i]]+'"' )
                        if ((data.defaults[keys[i]]=="auto" && handsome_UI.mode =="dark") || data
                        .defaults[keys[i]] == true) print( ' checked="checked"' );
                        #> />
                        <i></i>
                    </label>

                    <span> <# if(data.defaults[keys[i]]=="auto") print(LocalConst.DARK_MODE_AUTO); else if(data
                      .sections.settings[keys[i]] == LocalConst.DARK_MODE) {print(LocalConst.DARK_MODE_FIXED)
                      }else print(data.sections.settings[keys[i]]);#></span>
                    <# if ( i == ( keys.length - 1 ) ) {print( ' <small id="auto_info"'); if(data.defaults[keys[i]]!=="auto") print(' style="display:none"') ;print('><i class="glyphicon glyphicon-info-sign" data-toggle="tooltip" data-placement="bottom" data-original-title="网站深色模式自动依据您的设备关于深色模式的设置进行切换"></i></small>')}; #>
                </div>
                <# } #>
            </div>
            <div class="wrapper b-t b-light bg-light lter r-b">
                <div class="row row-sm">
                    <div class="col-xs-4">
                        <#
                        _.each( data.sections.colors, function( color, i ) {
                        var newColumnBefore = ( i % 5 ) === 4;
                        #>
                        <label class="i-checks block<# if ( !newColumnBefore ) print( ' m-b-sm' ); #>">
                            <input type="radio" name="color" value="{{ i }}"<# if ( data.defaults['color'] === i ) print( ' checked="checked"' ); #> />
                            <span class="block bg-light clearfix pos-rlt">
								<span class="active pos-abt w-full h-full bg-black-opacity text-center">
									<i class="fontello fontello-check text-md text-white m-t-xs"></i>
								</span>
								<b class="{{ color.navbarHeader }} header"></b>
								<b class="{{ color.navbarCollapse }} header"></b>
								<b class="{{ color.aside.replace( ' b-r', '' ) }}"></b>
							</span>
                        </label>
                        <#
                        if ( newColumnBefore && ( i + 1 ) < data.sections.colors.length )
                        print( '</div><div class="col-xs-4">' );
                        } );
                        #>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </script>
<div class="topButton panel panel-default">
    <button id="goToTop" class=" btn btn-default rightSettingBtn  pos-abt hide
          border-radius-half-left"
            data-toggle="tooltip" data-placement="left" data-original-title="返回顶部">
        <span class="settings-icon2"><i width="13px" height="13px" data-feather="corner-right-up"></i></span>
        <!--              <i class="fontello fontello-chevron-circle-up" aria-hidden="true"></i>-->
    </button>
</div>
    <div class="tag_toc_body hide">
        <div class="tocify-mobile-panel panel panel-default setting_body_panel right_panel" aria-hidden="true">
            <button class="rightSettingBtn border-radius-half-left btn btn-default pos-abt "
                    data-toggle="tooltip"
                    data-placement="left"
                    data-original-title="目录" data-toggle-class=".tocify-mobile-panel=active,
                    .settings=false">
                <span class="settings-icon2"><i width="13px" height="13px" data-feather="list"></i></span>
            </button>
            <div class="panel-heading">文章目录</div>
            <div class="setting_body toc-mobile-body">
                <div class="panel-body">
                    <div id="tocTree" class="tocTree"></div>
                </div>
            </div>
        </div>
    </div>

<footer id="footer" class="app-footer" role="footer">
    <div class="padder-sm bg-white footer_wrapper box-shadow-wrap-normal b-normal">
        <div class="pull-right hidden-xs text-ellipsis">
                                     <a href="https://typecho.org/" style="margin-left: 5px" target="_blank">
                <svg style="width: 16px;height: 16px;vertical-align: -4px;" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="30px" height="26px" viewBox="0 0 30 26" version="1.1">
                    <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">

                        <path d="M13,26 C3.36833333,26 0,22.631 0,13 C0,3.36866667 3.36833333,0 13,0 C22.6316667,0 26,3.36866667 26,13 C26,22.631 22.6316667,26 13,26 Z M6,9 L20,9 L20,7 L6,7 L6,9 Z M6,14 L16,14 L16,12 L6,12 L6,14 Z M6,19 L18,19 L18,17 L6,17 L6,19 Z" id="icon" fill="#000000" sketch:type="MSShapeGroup"/>
                    </g>
                </svg>
            </a>
            <a class="highlightlink" href="https://www.ihewro.com/archives/489/" target="_blank">
                <span>Theme by handsome</span>
            </a>
                    </div>
        <span class="text-ellipsis">&copy;&nbsp;2024 All rights reserved.
                        </span>
    </div>

</footer>



  </div><!--end of .app app-header-fixed-->




        

<!--定义全局变量-->


<style>
    .setting_body .panel-body .m-b-sm{
        display: none;
    }
    .setting_body .panel-body ~ .wrapper{
        display: none;
    }
</style>

<!--主题核心js-->





    <script src="https://www.ioiox.com/usr/themes/handsome/assets/js/function.min.js?v=9.2.120230801501"></script>

    <script src="https://www.ioiox.com/usr/themes/handsome/assets/js/core.min.js?v=9.2.120230801501"></script>



<script>
    $(function () {
        if ('serviceWorker' in navigator) {
            if (LocalConst.USE_CACHE) {
                navigator.serviceWorker.addEventListener('controllerchange', function (ev) {
                    try {
                        if (LocalConst.SERVICE_WORKER_INSTALLED){
                            $.message({
                                title:"检测到本地缓存需要更新",
                                message:"<a href='#' onclick='window.location.reload();'>点击刷新页面</a>更新本地缓存",
                                type:'warning',
                                time: '300000'
                            });
                        }else{
                            console.log("controllerchange:first sw install success");
                        }
                    }catch (e) {
                        console.log("controllerchange error",e);
                    }
                });
            }
        }
    })
</script>

<!--主题组件js加载-->
    <script src="https://www.ioiox.com/usr/themes/handsome/assets/js/features/jquery.pjax.min.js" type="text/javascript"></script>



<!--pjax动画组件-->






<!--主题组件js加载结束-->

<!--用户自定义js-->
<script type="text/javascript">
    try{
            }catch (e){
        handsome_util.settingError("外观设置————开发者设置——自定义js");
        console.error(e);
    }
</script>



</body>
</html><!--html end-->
  	<!-- / footer -->

