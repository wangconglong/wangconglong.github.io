# wangconglong.github.io
a personal website about Monty Hall Problem



<html lang="en">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <meta name="mobile-web-app-capable" content="yes">
    <title>
        Monty Hall Problem - HackMD
    </title>
    <link rel="icon" type="image/png" href="https://hackmd.io/favicon.png">
    <link rel="apple-touch-icon" href="https://hackmd.io/apple-touch-icon.png">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha256-916EbMg70RQy9LHiGkXzG8hSg9EdNy97GazNG/aiY1w=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha256-eZrrJcwDc/3uDhsdt61sL2oOBY362qM3lon1gyExkL0=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/ionicons/2.0.1/css/ionicons.min.css" integrity="sha256-3iu9jgsy9TpTwXKb7bNQzqWekRX7pPK+2OLj3R922fo=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/octicons/3.5.0/octicons.min.css" integrity="sha256-QiWfLIsCT02Sdwkogf6YMiQlj4NE84MKkzEMkZnMGdg=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.5.1/themes/prism.min.css" integrity="sha256-vtR0hSWRc3Tb26iuN2oZHt3KRUomwTufNIf5/4oeCyg=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@hackmd/emojify.js@2.1.0/dist/css/basic/emojify.min.css" integrity="sha256-UOrvMOsSDSrW6szVLe8ZDZezBxh5IoIfgTwdNDgTjiU=" crossorigin="anonymous" />
    <style>
        @import url(https://fonts.googleapis.com/css?family=Roboto:300,300i,400,400i,500,500i|Source+Code+Pro:300,400,500|Source+Sans+Pro:300,300i,400,400i,600,600i|Source+Serif+Pro&subset=latin-ext);.hljs{background:#fff;color:#333;display:block;overflow-x:auto;padding:.5em}.hljs-comment,.hljs-meta{color:#969896}.hljs-emphasis,.hljs-quote,.hljs-string,.hljs-strong,.hljs-template-variable,.hljs-variable{color:#df5000}.hljs-keyword,.hljs-selector-tag,.hljs-type{color:#a71d5d}.hljs-attribute,.hljs-bullet,.hljs-literal,.hljs-number,.hljs-symbol{color:#0086b3}.hljs-built_in,.hljs-builtin-name{color:#005cc5}.hljs-name,.hljs-section{color:#63a35c}.hljs-tag{color:#333}.hljs-attr,.hljs-selector-attr,.hljs-selector-class,.hljs-selector-id,.hljs-selector-pseudo,.hljs-title{color:#795da3}.hljs-addition{background-color:#eaffea;color:#55a532}.hljs-deletion{background-color:#ffecec;color:#bd2c00}.hljs-link{text-decoration:underline}.markdown-body{word-wrap:break-word;font-size:16px;line-height:1.5}.markdown-body:after,.markdown-body:before{content:"";display:table}.markdown-body:after{clear:both}.markdown-body>:first-child{margin-top:0!important}.markdown-body>:last-child{margin-bottom:0!important}.markdown-body a:not([href]){color:inherit;text-decoration:none}.markdown-body .absent{color:#c00}.markdown-body .anchor{float:left;line-height:1;margin-left:-20px;padding-right:4px}.markdown-body .anchor:focus{outline:none}.markdown-body blockquote,.markdown-body dl,.markdown-body ol,.markdown-body p,.markdown-body pre,.markdown-body table,.markdown-body ul{margin-bottom:16px;margin-top:0}.markdown-body hr{background-color:#e7e7e7;border:0;height:.25em;margin:24px 0;padding:0}.markdown-body blockquote{border-left:.25em solid #ddd;color:#777;font-size:16px;padding:0 1em}.markdown-body blockquote>:first-child{margin-top:0}.markdown-body blockquote>:last-child{margin-bottom:0}.markdown-body kbd,.popover kbd{background-color:#fcfcfc;border:1px solid;border-color:#ccc #ccc #bbb;border-radius:3px;box-shadow:inset 0 -1px 0 #bbb;color:#555;display:inline-block;font-size:11px;line-height:10px;padding:3px 5px;vertical-align:middle}.markdown-body .loweralpha{list-style-type:lower-alpha}.markdown-body h1,.markdown-body h2,.markdown-body h3,.markdown-body h4,.markdown-body h5,.markdown-body h6{font-weight:600;line-height:1.25;margin-bottom:16px;margin-top:24px}.markdown-body h1 .octicon-link,.markdown-body h2 .octicon-link,.markdown-body h3 .octicon-link,.markdown-body h4 .octicon-link,.markdown-body h5 .octicon-link,.markdown-body h6 .octicon-link{color:#000;vertical-align:middle;visibility:hidden}.markdown-body h1:hover .anchor,.markdown-body h2:hover .anchor,.markdown-body h3:hover .anchor,.markdown-body h4:hover .anchor,.markdown-body h5:hover .anchor,.markdown-body h6:hover .anchor{text-decoration:none}.markdown-body h1:hover .anchor .octicon-link,.markdown-body h2:hover .anchor .octicon-link,.markdown-body h3:hover .anchor .octicon-link,.markdown-body h4:hover .anchor .octicon-link,.markdown-body h5:hover .anchor .octicon-link,.markdown-body h6:hover .anchor .octicon-link{visibility:visible}.markdown-body h1 code,.markdown-body h1 tt,.markdown-body h2 code,.markdown-body h2 tt,.markdown-body h3 code,.markdown-body h3 tt,.markdown-body h4 code,.markdown-body h4 tt,.markdown-body h5 code,.markdown-body h5 tt,.markdown-body h6 code,.markdown-body h6 tt{font-size:inherit}.markdown-body h1{font-size:2em}.markdown-body h1,.markdown-body h2{border-bottom:1px solid #eee;padding-bottom:.3em}.markdown-body h2{font-size:1.5em}.markdown-body h3{font-size:1.25em}.markdown-body h4{font-size:1em}.markdown-body h5{font-size:.875em}.markdown-body h6{color:#777;font-size:.85em}.markdown-body ol,.markdown-body ul{padding-left:2em}.markdown-body ol.no-list,.markdown-body ul.no-list{list-style-type:none;padding:0}.markdown-body ol ol,.markdown-body ol ul,.markdown-body ul ol,.markdown-body ul ul{margin-bottom:0;margin-top:0}.markdown-body li>p{margin-top:16px}.markdown-body li+li{padding-top:.25em}.markdown-body dl{padding:0}.markdown-body dl dt{font-size:1em;font-style:italic;font-weight:700;margin-top:16px;padding:0}.markdown-body dl dd{margin-bottom:16px;padding:0 16px}.markdown-body table{display:block;overflow:auto;width:100%;word-break:normal;word-break:keep-all}.markdown-body table th{font-weight:700}.markdown-body table td,.markdown-body table th{border:1px solid #ddd;padding:6px 13px}.markdown-body table tr{background-color:#fff;border-top:1px solid #ccc}.markdown-body table tr:nth-child(2n){background-color:#f8f8f8}.markdown-body img{background-color:#fff;box-sizing:initial;max-width:100%}.markdown-body img[align=right]{padding-left:20px}.markdown-body img[align=left]{padding-right:20px}.markdown-body .emoji{background-color:initial;max-width:none;vertical-align:text-top}.markdown-body span.frame{display:block;overflow:hidden}.markdown-body span.frame>span{border:1px solid #ddd;display:block;float:left;margin:13px 0 0;overflow:hidden;padding:7px;width:auto}.markdown-body span.frame span img{display:block;float:left}.markdown-body span.frame span span{clear:both;color:#333;display:block;padding:5px 0 0}.markdown-body span.align-center{clear:both;display:block;overflow:hidden}.markdown-body span.align-center>span{display:block;margin:13px auto 0;overflow:hidden;text-align:center}.markdown-body span.align-center span img{margin:0 auto;text-align:center}.markdown-body span.align-right{clear:both;display:block;overflow:hidden}.markdown-body span.align-right>span{display:block;margin:13px 0 0;overflow:hidden;text-align:right}.markdown-body span.align-right span img{margin:0;text-align:right}.markdown-body span.float-left{display:block;float:left;margin-right:13px;overflow:hidden}.markdown-body span.float-left span{margin:13px 0 0}.markdown-body span.float-right{display:block;float:right;margin-left:13px;overflow:hidden}.markdown-body span.float-right>span{display:block;margin:13px auto 0;overflow:hidden;text-align:right}.markdown-body code,.markdown-body tt{background-color:#0000000a;border-radius:3px;font-size:85%;margin:0;padding:.2em 0}.markdown-body code:after,.markdown-body code:before,.markdown-body tt:after,.markdown-body tt:before{content:"\00a0";letter-spacing:-.2em}.markdown-body code br,.markdown-body tt br{display:none}.markdown-body del code{text-decoration:inherit}.markdown-body pre{word-wrap:normal}.markdown-body pre>code{background:#0000;border:0;font-size:100%;margin:0;padding:0;white-space:pre;word-break:normal}.markdown-body .highlight{margin-bottom:16px}.markdown-body .highlight pre{margin-bottom:0;word-break:normal}.markdown-body .highlight pre,.markdown-body pre{background-color:#f7f7f7;border-radius:3px;font-size:85%;line-height:1.45;overflow:auto;padding:16px}.markdown-body pre code,.markdown-body pre tt{word-wrap:normal;background-color:initial;border:0;display:inline;line-height:inherit;margin:0;max-width:auto;overflow:visible;padding:0}.markdown-body pre code:after,.markdown-body pre code:before,.markdown-body pre tt:after,.markdown-body pre tt:before{content:normal}.markdown-body .csv-data td,.markdown-body .csv-data th{font-size:12px;line-height:1;overflow:hidden;padding:5px;text-align:left;white-space:nowrap}.markdown-body .csv-data .blob-line-num{background:#fff;border:0;padding:10px 8px 9px;text-align:right}.markdown-body .csv-data tr{border-top:0}.markdown-body .csv-data th{background:#f8f8f8;border-top:0;font-weight:700}.news .alert .markdown-body blockquote{border:0;padding:0 0 0 40px}.activity-tab .news .alert .commits,.activity-tab .news .markdown-body blockquote{padding-left:0}.task-list-item{list-style-type:none}.task-list-item label{font-weight:400}.task-list-item.enabled label{cursor:pointer}.task-list-item+.task-list-item{margin-top:3px}.task-list-item-checkbox{cursor:default!important;float:left;margin:.31em 0 .2em -1.3em!important;vertical-align:middle}.markdown-body{max-width:758px;overflow:visible!important;padding-bottom:40px;padding-top:40px;position:relative}.markdown-body .emoji{vertical-align:top}.markdown-body pre{border:inherit!important}.markdown-body code{color:inherit!important}.markdown-body pre code .wrapper{display:-moz-inline-flex;display:-ms-inline-flex;display:-o-inline-flex;display:inline-flex}.markdown-body pre code .gutter{float:left;overflow:hidden;-webkit-user-select:none;user-select:none}.markdown-body pre code .gutter.linenumber{border-right:3px solid #6ce26c!important;box-sizing:initial;color:#afafaf!important;cursor:default;display:inline-block;min-width:20px;padding:0 8px 0 0;position:relative;text-align:right;z-index:4}.markdown-body pre code .gutter.linenumber>span:before{content:attr(data-linenumber)}.markdown-body pre code .code{float:left;margin:0 0 0 16px}.markdown-body .gist .line-numbers{border-bottom:none;border-left:none;border-top:none}.markdown-body .gist .line-data{border:none}.markdown-body .gist table{border-collapse:inherit!important;border-spacing:0}.markdown-body code[data-gist-id]{background:none;padding:0}.markdown-body code[data-gist-id]:after,.markdown-body code[data-gist-id]:before{content:""}.markdown-body code[data-gist-id] .blob-num{border:unset}.markdown-body code[data-gist-id] table{margin-bottom:unset;overflow:unset}.markdown-body code[data-gist-id] table tr{background:unset}.markdown-body[dir=rtl] pre{direction:ltr}.markdown-body[dir=rtl] code{direction:ltr;unicode-bidi:embed}.markdown-body .alert>p:last-child{margin-bottom:0}.markdown-body pre.abc,.markdown-body pre.flow-chart,.markdown-body pre.graphviz,.markdown-body pre.mermaid,.markdown-body pre.sequence-diagram,.markdown-body pre.vega{background-color:inherit;border-radius:0;overflow:visible;text-align:center;white-space:inherit}.markdown-body pre.abc>code,.markdown-body pre.flow-chart>code,.markdown-body pre.graphviz>code,.markdown-body pre.mermaid>code,.markdown-body pre.sequence-diagram>code,.markdown-body pre.vega>code{text-align:left}.markdown-body pre.abc>svg,.markdown-body pre.flow-chart>svg,.markdown-body pre.graphviz>svg,.markdown-body pre.mermaid>svg,.markdown-body pre.sequence-diagram>svg,.markdown-body pre.vega>svg{height:100%;max-width:100%}.markdown-body pre>code.wrap{word-wrap:break-word;white-space:pre-wrap;white-space:-moz-pre-wrap;white-space:-pre-wrap;white-space:-o-pre-wrap}.markdown-body .alert>p:last-child,.markdown-body .alert>ul:last-child{margin-bottom:0}.markdown-body summary{display:list-item}.markdown-body summary:focus{outline:none}.markdown-body details summary{cursor:pointer}.markdown-body details:not([open])>:not(summary){display:none}.markdown-body figure{margin:1em 40px}.markdown-body .mark,.markdown-body mark{background-color:#fff1a7}.vimeo,.youtube{background-color:#000;background-position:50%;background-repeat:no-repeat;background-size:contain;cursor:pointer;display:table;overflow:hidden;text-align:center}.vimeo,.youtube{position:relative;width:100%}.youtube{padding-bottom:56.25%}.vimeo img{object-fit:contain;width:100%;z-index:0}.youtube img{object-fit:cover;z-index:0}.vimeo iframe,.youtube iframe,.youtube img{height:100%;left:0;position:absolute;top:0;width:100%}.vimeo iframe,.youtube iframe{vertical-align:middle;z-index:1}.vimeo .icon,.youtube .icon{color:#fff;height:auto;left:50%;opacity:.3;position:absolute;top:50%;transform:translate(-50%,-50%);transition:opacity .2s;width:auto;z-index:0}.vimeo:hover .icon,.youtube:hover .icon{opacity:.6;transition:opacity .2s}.slideshare .inner,.speakerdeck .inner{position:relative;width:100%}.slideshare .inner iframe,.speakerdeck .inner iframe{bottom:0;height:100%;left:0;position:absolute;right:0;top:0;width:100%}.figma{display:table;padding-bottom:56.25%;position:relative;width:100%}.figma iframe{border:1px solid #eee;bottom:0;height:100%;left:0;position:absolute;right:0;top:0;width:100%}.markmap-container{height:300px}.markmap-container>svg{height:100%;width:100%}.MJX_Assistive_MathML{display:none}#MathJax_Message{z-index:1000!important}.ui-infobar{color:#777;margin:25px auto -25px;max-width:760px;position:relative;z-index:2}.toc .invisable-node{list-style-type:none}.ui-toc{bottom:20px;position:fixed;z-index:998}.ui-toc.both-mode{margin-left:8px}.ui-toc.both-mode .ui-toc-label{border-bottom-left-radius:0;border-top-left-radius:0;height:40px;padding:10px 4px}.ui-toc-label{background-color:#e6e6e6;border:none;color:#868686;transition:opacity .2s}.ui-toc .open .ui-toc-label{color:#fff;opacity:1;transition:opacity .2s}.ui-toc-label:focus{background-color:#ccc;color:#000;opacity:.3}.ui-toc-label:hover{background-color:#ccc;opacity:1;transition:opacity .2s}.ui-toc-dropdown{margin-bottom:20px;margin-top:20px;max-height:70vh;max-width:45vw;overflow:auto;padding-left:10px;padding-right:10px;text-align:inherit;width:25vw}.ui-toc-dropdown>.toc{max-height:calc(70vh - 100px);overflow:auto}.ui-toc-dropdown[dir=rtl] .nav{letter-spacing:.0029em;padding-right:0}.ui-toc-dropdown a{overflow:hidden;text-overflow:ellipsis;white-space:pre}.ui-toc-dropdown .nav>li>a{color:#767676;display:block;font-size:13px;font-weight:500;padding:4px 20px}.ui-toc-dropdown .nav>li:first-child:last-child>ul,.ui-toc-dropdown .toc.expand ul{display:block}.ui-toc-dropdown .nav>li>a:focus,.ui-toc-dropdown .nav>li>a:hover{background-color:initial;border-left:1px solid #000;color:#000;padding-left:19px;text-decoration:none}.ui-toc-dropdown[dir=rtl] .nav>li>a:focus,.ui-toc-dropdown[dir=rtl] .nav>li>a:hover{border-left:none;border-right:1px solid #000;padding-right:19px}.ui-toc-dropdown .nav>.active:focus>a,.ui-toc-dropdown .nav>.active:hover>a,.ui-toc-dropdown .nav>.active>a{background-color:initial;border-left:2px solid #000;color:#000;font-weight:700;padding-left:18px}.ui-toc-dropdown[dir=rtl] .nav>.active:focus>a,.ui-toc-dropdown[dir=rtl] .nav>.active:hover>a,.ui-toc-dropdown[dir=rtl] .nav>.active>a{border-left:none;border-right:2px solid #000;padding-right:18px}.ui-toc-dropdown .nav .nav{display:none;padding-bottom:10px}.ui-toc-dropdown .nav>.active>ul{display:block}.ui-toc-dropdown .nav .nav>li>a{font-size:12px;font-weight:400;padding-bottom:1px;padding-left:30px;padding-top:1px}.ui-toc-dropdown[dir=rtl] .nav .nav>li>a{padding-right:30px}.ui-toc-dropdown .nav .nav>li>ul>li>a{font-size:12px;font-weight:400;padding-bottom:1px;padding-left:40px;padding-top:1px}.ui-toc-dropdown[dir=rtl] .nav .nav>li>ul>li>a{padding-right:40px}.ui-toc-dropdown .nav .nav>li>a:focus,.ui-toc-dropdown .nav .nav>li>a:hover{padding-left:29px}.ui-toc-dropdown[dir=rtl] .nav .nav>li>a:focus,.ui-toc-dropdown[dir=rtl] .nav .nav>li>a:hover{padding-right:29px}.ui-toc-dropdown .nav .nav>li>ul>li>a:focus,.ui-toc-dropdown .nav .nav>li>ul>li>a:hover{padding-left:39px}.ui-toc-dropdown[dir=rtl] .nav .nav>li>ul>li>a:focus,.ui-toc-dropdown[dir=rtl] .nav .nav>li>ul>li>a:hover{padding-right:39px}.ui-toc-dropdown .nav .nav>.active:focus>a,.ui-toc-dropdown .nav .nav>.active:hover>a,.ui-toc-dropdown .nav .nav>.active>a{font-weight:500;padding-left:28px}.ui-toc-dropdown[dir=rtl] .nav .nav>.active:focus>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active:hover>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active>a{padding-right:28px}.ui-toc-dropdown .nav .nav>.active>.nav>.active:focus>a,.ui-toc-dropdown .nav .nav>.active>.nav>.active:hover>a,.ui-toc-dropdown .nav .nav>.active>.nav>.active>a{font-weight:500;padding-left:38px}.ui-toc-dropdown[dir=rtl] .nav .nav>.active>.nav>.active:focus>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active>.nav>.active:hover>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active>.nav>.active>a{padding-right:38px}.markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html[lang^=ja] .markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ ゴシック,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html[lang=zh-tw] .markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html[lang=zh-cn] .markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html .markdown-body[lang^=ja]{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ ゴシック,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html .markdown-body[lang=zh-tw]{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html .markdown-body[lang=zh-cn]{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html[lang^=ja] .ui-toc-dropdown{font-family:Source Sans Pro,Helvetica,Arial,Meiryo UI,MS PGothic,ＭＳ Ｐゴシック,sans-serif}html[lang=zh-tw] .ui-toc-dropdown{font-family:Source Sans Pro,Helvetica,Arial,Microsoft JhengHei UI,微軟正黑UI,sans-serif}html[lang=zh-cn] .ui-toc-dropdown{font-family:Source Sans Pro,Helvetica,Arial,Microsoft YaHei UI,微软雅黑UI,sans-serif}html .ui-toc-dropdown[lang^=ja]{font-family:Source Sans Pro,Helvetica,Arial,Meiryo UI,MS PGothic,ＭＳ Ｐゴシック,sans-serif}html .ui-toc-dropdown[lang=zh-tw]{font-family:Source Sans Pro,Helvetica,Arial,Microsoft JhengHei UI,微軟正黑UI,sans-serif}html .ui-toc-dropdown[lang=zh-cn]{font-family:Source Sans Pro,Helvetica,Arial,Microsoft YaHei UI,微软雅黑UI,sans-serif}.ui-affix-toc{max-height:70vh;max-width:15vw;overflow:auto;position:fixed;top:0}.back-to-top,.expand-toggle,.go-to-bottom{color:#999;display:block;font-size:12px;font-weight:500;margin-left:10px;margin-top:10px;padding:4px 10px}.back-to-top:focus,.back-to-top:hover,.expand-toggle:focus,.expand-toggle:hover,.go-to-bottom:focus,.go-to-bottom:hover{color:#563d7c;text-decoration:none}.back-to-top,.go-to-bottom{margin-top:0}.ui-user-icon{background-position:50%;background-repeat:no-repeat;background-size:cover;border-radius:50%;display:block;height:20px;margin-bottom:2px;margin-right:5px;margin-top:2px;width:20px}.ui-user-icon.small{display:inline-block;height:18px;margin:0 0 .2em;vertical-align:middle;width:18px}.ui-infobar>small>span{line-height:22px}.ui-infobar>small .dropdown{display:inline-block}.ui-infobar>small .dropdown a:focus,.ui-infobar>small .dropdown a:hover{text-decoration:none}.ui-more-info{color:#888;cursor:pointer;vertical-align:middle}.ui-more-info .fa{font-size:16px}.ui-connectedGithub,.ui-published-note{color:#888}.ui-connectedGithub{line-height:23px;white-space:nowrap}.ui-connectedGithub a.file-path{color:#888;padding-left:22px;text-decoration:none}.ui-connectedGithub a.file-path:active,.ui-connectedGithub a.file-path:hover{color:#888;text-decoration:underline}.ui-connectedGithub .fa{font-size:20px}.ui-published-note .fa{font-size:20px;vertical-align:top}.unselectable{-webkit-user-select:none;-o-user-select:none;user-select:none}.selectable{-webkit-user-select:text;-o-user-select:text;user-select:text}.inline-spoiler-section{cursor:pointer}.inline-spoiler-section .spoiler-text{background-color:#333;border-radius:2px}.inline-spoiler-section .spoiler-text>*{opacity:0}.inline-spoiler-section .spoiler-img{filter:blur(10px)}.inline-spoiler-section.raw{background-color:#333;border-radius:2px}.inline-spoiler-section.raw>*{opacity:0}.inline-spoiler-section.unveil{cursor:auto}.inline-spoiler-section.unveil .spoiler-text{background-color:#3333331a}.inline-spoiler-section.unveil .spoiler-text>*{opacity:1}.inline-spoiler-section.unveil .spoiler-img{filter:none}@media print{blockquote,div,img,pre,table{page-break-inside:avoid!important}a[href]:after{font-size:12px!important}}.markdown-body.slides{color:#222;position:relative;z-index:1}.markdown-body.slides:before{background-color:currentColor;bottom:0;box-shadow:0 0 0 50vw;content:"";display:block;left:0;position:absolute;right:0;top:0;z-index:-1}.markdown-body.slides section[data-markdown]{background-color:#fff;margin-bottom:1.5em;position:relative;text-align:center}.markdown-body.slides section[data-markdown] code{text-align:left}.markdown-body.slides section[data-markdown]:before{content:"";display:block;padding-bottom:56.23%}.markdown-body.slides section[data-markdown]>div:first-child{left:1em;max-height:100%;overflow:hidden;position:absolute;right:1em;top:50%;transform:translateY(-50%)}.markdown-body.slides section[data-markdown]>ul{display:inline-block}.markdown-body.slides>section>section+section:after{border:3px solid #777;content:"";height:1.5em;position:absolute;right:1em;top:-1.5em}.site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,sans-serif}html[lang^=ja] .site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ ゴシック,sans-serif}html[lang=zh-tw] .site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif}html[lang=zh-cn] .site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif}body{font-smoothing:subpixel-antialiased!important;-webkit-font-smoothing:subpixel-antialiased!important;-moz-osx-font-smoothing:auto!important;-webkit-overflow-scrolling:touch;font-family:Source Sans Pro,Helvetica,Arial,sans-serif;letter-spacing:.025em}html[lang^=ja] body{font-family:Source Sans Pro,Helvetica,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ ゴシック,sans-serif}html[lang=zh-tw] body{font-family:Source Sans Pro,Helvetica,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif}html[lang=zh-cn] body{font-family:Source Sans Pro,Helvetica,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif}abbr[title]{border-bottom:none;text-decoration:underline;-webkit-text-decoration:underline dotted;text-decoration:underline dotted}abbr[data-original-title],abbr[title]{cursor:help}body.modal-open{overflow-y:auto;padding-right:0!important}svg{text-shadow:none}
    </style>
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
    	<script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.min.js" integrity="sha256-3Jy/GbSLrg0o9y5Z5n1uw0qxZECH7C6OQpVBgNFYa0g=" crossorigin="anonymous"></script>
    	<script src="https://cdnjs.cloudflare.com/ajax/libs/respond.js/1.4.2/respond.min.js" integrity="sha256-g6iAfvZp+nDQ2TdTR/VVKJf3bGro4ub5fvWSWVRi2NE=" crossorigin="anonymous"></script>
		<script src="https://cdnjs.cloudflare.com/ajax/libs/es5-shim/4.5.9/es5-shim.min.js" integrity="sha256-8E4Is26QH0bD52WoQpcB+R/tcWQtpzlCojrybUd7Mxo=" crossorigin="anonymous"></script>
    <![endif]-->
</head>

<body>
    <div id="doc" class="markdown-body container-fluid comment-inner comment-enabled" data-hard-breaks="false"><h1 id="Monty-Hall-Problem" data-id="Monty-Hall-Problem"><a class="anchor hidden-xs" href="#Monty-Hall-Problem" title="Monty-Hall-Problem"><span class="octicon octicon-link"></span></a><span>Monty Hall Problem</span></h1><p><span>The Monty Hall problem is a brain-teaser, in the form of a probability puzzle, loosely based on the American television game show Let’s Make a Deal and named after its original host, Monty Hall.</span></p><h2 id="Define-a-Monty-Hall-Problem-as-a-Python-function" data-id="Define-a-Monty-Hall-Problem-as-a-Python-function"><a class="anchor hidden-xs" href="#Define-a-Monty-Hall-Problem-as-a-Python-function" title="Define-a-Monty-Hall-Problem-as-a-Python-function"><span class="octicon octicon-link"></span></a><span>Define a Monty Hall Problem as a Python function</span></h2><ul>
<li><span>Input: your initial selection from [0,1,2]; and your decision: {‘</span><strong><span>stay</span></strong><span>’, ‘</span><strong><span>switch</span></strong><span>’}</span></li>
<li><span>Outcome: </span><code>win </code><span>or </span><code>lose</code></li>
</ul><h3 id="Style" data-id="Style"><a class="anchor hidden-xs" href="#Style" title="Style"><span class="octicon octicon-link"></span></a><span>Style</span></h3><ul>
<li><span>There are 3 doors, behind which are two goats and a car.</span></li>
<li><span>You pick a door (call it door A). You’re hoping for the car of course.</span></li>
<li><span>Monty Hall, the game show host, examines the other doors (B &amp; C) and opens one with a goat. (If both doors have goats, he picks randomly.)</span></li>
</ul><pre><code class="python hljs"><span class="hljs-keyword">import</span> numpy <span class="hljs-keyword">as</span> np
<span class="hljs-keyword">import</span> pandas <span class="hljs-keyword">as</span> pd
<span class="hljs-keyword">import</span> random

<span class="hljs-comment">## Define a Monty Hall Problem as a Python function</span>
<span class="hljs-keyword">def</span> <span class="hljs-title function_">MHGame</span>(<span class="hljs-params">door, d</span>):
  <span class="hljs-comment">## Step1: Setup the game with the door (with a Car)</span>
  out = np.zeros(<span class="hljs-number">3</span>)
  <span class="hljs-comment"># generate a door position with a car</span>
  door0 = random.randint(<span class="hljs-number">0</span>,<span class="hljs-number">2</span>)
  out[door0] = <span class="hljs-number">1</span>
  <span class="hljs-comment">## Step2: Your selection</span>
  <span class="hljs-built_in">print</span>(<span class="hljs-string">'Your selection is %d'</span> %door)
  <span class="hljs-comment">## Step3: Monty opens a door</span>
  res_door = <span class="hljs-built_in">set</span>([<span class="hljs-number">0</span>,<span class="hljs-number">1</span>,<span class="hljs-number">2</span>]) - <span class="hljs-built_in">set</span>([door0, door])
  open_door = random.choice(<span class="hljs-built_in">list</span>(res_door))
  <span class="hljs-built_in">print</span>(<span class="hljs-string">'Monty opens the door: %d'</span> %open_door)
  <span class="hljs-comment">## Step4: "stay" or "switch"</span>
  <span class="hljs-keyword">if</span> d == <span class="hljs-string">'stay'</span>:
    final_door = door
    <span class="hljs-built_in">print</span>(<span class="hljs-string">'Your decision is to stay...'</span>)
    final_out = out[final_door]
  <span class="hljs-keyword">elif</span> d == <span class="hljs-string">'switch'</span>:
    <span class="hljs-built_in">print</span>(<span class="hljs-string">'Your decision is to switch...'</span>)
    final_door = <span class="hljs-built_in">list</span>(<span class="hljs-built_in">set</span>([<span class="hljs-number">0</span>,<span class="hljs-number">1</span>,<span class="hljs-number">2</span>]) - <span class="hljs-built_in">set</span>([door, open_door]))[<span class="hljs-number">0</span>]
    final_out = out[final_door]
  <span class="hljs-keyword">else</span>:
    <span class="hljs-built_in">print</span>(<span class="hljs-string">'Please input d with stay or switch.'</span>)
  <span class="hljs-built_in">print</span>(<span class="hljs-string">'The true door is: %d; your final seletion is: %d'</span> %(door0, final_door))
  <span class="hljs-keyword">if</span> final_out == <span class="hljs-number">1</span>:
    <span class="hljs-built_in">print</span>(<span class="hljs-string">'You win!'</span>)
  <span class="hljs-keyword">else</span>:
    <span class="hljs-built_in">print</span>(<span class="hljs-string">'Sorry, you lose.'</span>)
  <span class="hljs-keyword">return</span> final_out
</code></pre><h3 id="Test-the-function" data-id="Test-the-function"><a class="anchor hidden-xs" href="#Test-the-function" title="Test-the-function"><span class="octicon octicon-link"></span></a><span>Test the function</span></h3><p><code>MHGame(door=0, d='switch')</code></p><pre><code>Your selection is 0
Monty opens the door: 2
Your decision is to switch...
The true door is: 1; your final seletion is: 1
You win!
1.0
</code></pre><h2 id="Statistical-simulation" data-id="Statistical-simulation"><a class="anchor hidden-xs" href="#Statistical-simulation" title="Statistical-simulation"><span class="octicon octicon-link"></span></a><span>Statistical simulation</span></h2><p><span>Attempt </span><code>MHGame</code><span> by 1000 times, with different options, to see the prob of </span><code>win</code></p><pre><code>res = {'door': [], 'decision': [], 'out': []}
n_trial = 1000
for i in range(n_trial):
  for d in ['stay', 'switch']:
    for door in [0, 1, 2]:
      out_tmp = MHGame(door=door, d=d)
      res['door'].append(door)
      res['decision'].append(d)
      res['out'].append(out_tmp)
</code></pre><p><code>res = pd.DataFrame(res)</code>
<code>res.head(5)</code></p><table>
<thead>
<tr>
<th><span>door</span></th>
<th><span>decision</span></th>
<th><span>out</span></th>
</tr>
</thead>
<tbody>
<tr>
<td><span>0</span></td>
<td><span>0</span></td>
<td><span>stay</span></td>
</tr>
<tr>
<td><span>1</span></td>
<td><span>1</span></td>
<td><span>stay</span></td>
</tr>
<tr>
<td><span>2</span></td>
<td><span>2</span></td>
<td><span>stay</span></td>
</tr>
<tr>
<td><span>3</span></td>
<td><span>0</span></td>
<td><span>switch</span></td>
</tr>
<tr>
<td><span>4</span></td>
<td><span>1</span></td>
<td><span>switch</span></td>
</tr>
</tbody>
</table><h2 id="Analyze-the-results" data-id="Analyze-the-results"><a class="anchor hidden-xs" href="#Analyze-the-results" title="Analyze-the-results"><span class="octicon octicon-link"></span></a><span>Analyze the results</span></h2><ul>
<li><span>Compute the conditional probability</span></li>
<li><span>Visualize the results</span></li>
</ul><pre><code>for d in ['stay', 'switch']:
  freq_tmp = res[res['decision'] == d]['out'].mean()
  print('The conditional prob given %s is %f' %(d, freq_tmp))
</code></pre><pre><code>The conditional prob given stay is 0.328000
The conditional prob given switch is 0.676667
</code></pre><pre><code>sum_res = res.groupby(['door', 'decision'])['out'].mean()
sum_res
</code></pre><table>
<thead>
<tr>
<th><span>door</span></th>
<th><span>decision</span></th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td><span>0</span></td>
<td><span>stay</span></td>
<td><span>0.321</span></td>
</tr>
<tr>
<td></td>
<td><span>switch</span></td>
<td><span>0.674</span></td>
</tr>
<tr>
<td><span>1</span></td>
<td><span>stay</span></td>
<td><span>0.320</span></td>
</tr>
<tr>
<td></td>
<td><span>switch</span></td>
<td><span>0.669</span></td>
</tr>
<tr>
<td><span>2</span></td>
<td><span>stay</span></td>
<td><span>0.343</span></td>
</tr>
<tr>
<td></td>
<td><span>switch</span></td>
<td><span>0.687</span></td>
</tr>
</tbody>
</table><p><code>Name: out, dtype: float64</code></p><h2 id="Histgram-decision-matters" data-id="Histgram-decision-matters"><a class="anchor hidden-xs" href="#Histgram-decision-matters" title="Histgram-decision-matters"><span class="octicon octicon-link"></span></a><span>Histgram: decision matters?</span></h2><pre><code>import seaborn as sns
sns.displot(data=res, x='out', col='decision', hue='decision', stat='probability')
</code></pre><p><code>&lt;seaborn.axisgrid.FacetGrid at 0x7f2fc06f4430&gt;</code>
<img src="https://i.imgur.com/c0h5Zh7.png" alt="displot" loading="lazy"></p><h2 id="Histgram-initial-door-matters" data-id="Histgram-initial-door-matters"><a class="anchor hidden-xs" href="#Histgram-initial-door-matters" title="Histgram-initial-door-matters"><span class="octicon octicon-link"></span></a><span>Histgram: initial door matters?</span></h2><pre><code>import seaborn as sns
sns.displot(data=res, x='out', col='door', hue='door', stat='probability')
</code></pre><p><code>&lt;seaborn.axisgrid.FacetGrid at 0x7f2fc054f9d0&gt;</code>
<img src="https://i.imgur.com/8TWZTDf.png" alt="displot" loading="lazy"></p><pre><code>sum_res = res.groupby(['door', 'decision']).mean().reset_index()
sum_res
</code></pre><table>
<thead>
<tr>
<th><span>door</span></th>
<th><span>door</span></th>
<th><span>decision</span></th>
<th><span>out</span></th>
</tr>
</thead>
<tbody>
<tr>
<td><span>0</span></td>
<td><span>0</span></td>
<td><span>stay</span></td>
<td><span>0.321</span></td>
</tr>
<tr>
<td><span>1</span></td>
<td><span>0</span></td>
<td><span>switch</span></td>
<td><span>0.674</span></td>
</tr>
<tr>
<td><span>2</span></td>
<td><span>1</span></td>
<td><span>stay</span></td>
<td><span>0.320</span></td>
</tr>
<tr>
<td><span>3</span></td>
<td><span>1</span></td>
<td><span>switch</span></td>
<td><span>0.669</span></td>
</tr>
<tr>
<td><span>4</span></td>
<td><span>2</span></td>
<td><span>stay</span></td>
<td><span>0.343</span></td>
</tr>
<tr>
<td><span>5</span></td>
<td><span>2</span></td>
<td><span>switch</span></td>
<td><span>0.687</span></td>
</tr>
</tbody>
</table><h2 id="Probabilistic-interpretation1" data-id="Probabilistic-interpretation1"><a class="anchor hidden-xs" href="#Probabilistic-interpretation1" title="Probabilistic-interpretation1"><span class="octicon octicon-link"></span></a><span>Probabilistic interpretation</span><sup class="footnote-ref"><a href="#fn1" id="fnref1">[1]</a></sup></h2><p><span>A statistical perspective: we want to make a decision </span><span class="mathjax raw">\(D\)</span><span>: “stay” (=0) or “switch” (=1), to maximize the probability, that is,</span>
<span class="mathjax raw">\[
\max_{d = 0, 1} \mathbb{P}\big( Y = 1 \big| D = d \big).
\]</span>
<span>Thus, the primary goal is to compute the conditional probability. Clearly, </span><span class="mathjax raw">\(Y = 1\)</span><span> is highly depended on your choice in the first stage, let’s denote </span><span class="mathjax raw">\(X \in \{0, 1\}\)</span><span> as your initial selection with or w/o car. Then, we have</span>
<span class="mathjax raw">\[
    \mathbb{P}\big( Y = 1 | D =d \big) = \mathbb{P} \big( Y = 1, X = 0 | D =d \big) + \mathbb{P} \big( Y = 1, X = 1 | D =d \big) \\
    = \mathbb{P} \big( Y = 1, | X = 0, D =d \big) \mathbb{P}(X = 0) + \mathbb{P} \big( Y = 1 | X=1, D =d \big) \mathbb{P}(X = 1)
\]</span>
<span>where the first equality follows from the relation between marginal and joint probabilities, and the second equality follows Bayes’ theorem. Note that</span>
<span class="mathjax raw">\[
\mathbb{P}(X = 1) = \mathbb{P}(\text{initially select car}) = 1/3, \ \
\mathbb{P}(X = 0) = \mathbb{P}(\text{initially select goat}) = 2/3.
\]</span>
<span>Now, we compare the difference in the conditional probabilities when making different decisions.</span></p><ul>
<li><mark><span>D = ‘stay’</span></mark></li>
</ul><p><span class="mathjax raw">\[
\mathbb{P}( Y = 1 | D = 0 \big) = \frac{2}{3} \mathbb{P} \big( Y = 1 | X = 0, D=0 \big) + \frac{1}{3} \mathbb{P} \big( Y = 1 | X=1, D=0 \big) = \frac{1}{3}.
\]</span></p><ul>
<li><mark><span>D = ‘switch’</span></mark></li>
</ul><p><span class="mathjax raw">\[
\mathbb{P}( Y = 1 | D = 0 \big) = \frac{2}{3} \mathbb{P} \big( Y = 1 | X = 0, D=1 \big) + \frac{1}{3} \mathbb{P} \big( Y = 1 | X=1, D=1 \big) = \frac{2}{3}.
\]</span></p><hr class="footnotes-sep"><section class="footnotes">
<ol class="footnotes-list">
<li id="fn1" class="footnote-item"><p><code>latex</code><span>(</span><a href="https://www.youtube.com/watch?v=zqQM66uAig0" target="_blank" rel="noopener"><span>tutorial</span></a><span>) is required, which is optional (but highly recommended) for our course.</span> <a href="#fnref1" class="footnote-backref">↩︎</a></p>
</li>
</ol>
</section></div>
    <div class="ui-toc dropup unselectable hidden-print" style="display:none;">
        <div class="pull-right dropdown">
            <a id="tocLabel" class="ui-toc-label btn btn-default" data-toggle="dropdown" href="#" role="button" aria-haspopup="true" aria-expanded="false" title="Table of content">
                <i class="fa fa-bars"></i>
            </a>
            <ul id="ui-toc" class="ui-toc-dropdown dropdown-menu" aria-labelledby="tocLabel">
                <div class="toc"><ul class="nav">
<li><a href="#Monty-Hall-Problem" title="Monty Hall Problem">Monty Hall Problem</a><ul class="nav">
<li><a href="#Define-a-Monty-Hall-Problem-as-a-Python-function" title="Define a Monty Hall Problem as a Python function">Define a Monty Hall Problem as a Python function</a><ul class="nav">
<li><a href="#Style" title="Style">Style</a></li>
<li><a href="#Test-the-function" title="Test the function">Test the function</a></li>
</ul>
</li>
<li><a href="#Statistical-simulation" title="Statistical simulation">Statistical simulation</a></li>
<li><a href="#Analyze-the-results" title="Analyze the results">Analyze the results</a></li>
<li><a href="#Histgram-decision-matters" title="Histgram: decision matters?">Histgram: decision matters?</a></li>
<li><a href="#Histgram-initial-door-matters" title="Histgram: initial door matters?">Histgram: initial door matters?</a></li>
<li><a href="#Probabilistic-interpretation1" title="Probabilistic interpretation[1]">Probabilistic interpretation[1]</a></li>
</ul>
</li>
</ul>
</div><div class="toc-menu"><a class="expand-toggle" href="#">全部展開</a><a class="back-to-top" href="#">回到頂部</a><a class="go-to-bottom" href="#">移至底部</a></div>
            </ul>
        </div>
    </div>
    <div id="ui-toc-affix" class="ui-affix-toc ui-toc-dropdown unselectable hidden-print" data-spy="affix" style="top:17px;display:none;" null null>
        <div class="toc"><ul class="nav">
<li><a href="#Monty-Hall-Problem" title="Monty Hall Problem">Monty Hall Problem</a><ul class="nav">
<li><a href="#Define-a-Monty-Hall-Problem-as-a-Python-function" title="Define a Monty Hall Problem as a Python function">Define a Monty Hall Problem as a Python function</a><ul class="nav">
<li><a href="#Style" title="Style">Style</a></li>
<li><a href="#Test-the-function" title="Test the function">Test the function</a></li>
</ul>
</li>
<li><a href="#Statistical-simulation" title="Statistical simulation">Statistical simulation</a></li>
<li><a href="#Analyze-the-results" title="Analyze the results">Analyze the results</a></li>
<li><a href="#Histgram-decision-matters" title="Histgram: decision matters?">Histgram: decision matters?</a></li>
<li><a href="#Histgram-initial-door-matters" title="Histgram: initial door matters?">Histgram: initial door matters?</a></li>
<li><a href="#Probabilistic-interpretation1" title="Probabilistic interpretation[1]">Probabilistic interpretation[1]</a></li>
</ul>
</li>
</ul>
</div><div class="toc-menu"><a class="expand-toggle" href="#">全部展開</a><a class="back-to-top" href="#">回到頂部</a><a class="go-to-bottom" href="#">移至底部</a></div>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js" integrity="sha256-hVVnYaiADRTO2PzUGmuLJr8BLUSjGIZsDYGmIJLv2b8=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha256-U5ZEeKfGNOja007MMD3YBI0A3OSZOQbeG6z2f2Y0hu8=" crossorigin="anonymous" defer></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gist-embed/2.6.0/gist-embed.min.js" integrity="sha256-KyF2D6xPIJUW5sUDSs93vWyZm+1RzIpKCexxElmxl8g=" crossorigin="anonymous" defer></script>
    <script>
        var markdown = $(".markdown-body");
        //smooth all hash trigger scrolling
        function smoothHashScroll() {
            var hashElements = $("a[href^='#']").toArray();
            for (var i = 0; i < hashElements.length; i++) {
                var element = hashElements[i];
                var $element = $(element);
                var hash = element.hash;
                if (hash) {
                    $element.on('click', function (e) {
                        // store hash
                        var hash = this.hash;
                        if ($(hash).length <= 0) return;
                        // prevent default anchor click behavior
                        e.preventDefault();
                        // animate
                        $('body, html').stop(true, true).animate({
                            scrollTop: $(hash).offset().top
                        }, 100, "linear", function () {
                            // when done, add hash to url
                            // (default click behaviour)
                            window.location.hash = hash;
                        });
                    });
                }
            }
        }

        smoothHashScroll();
        var toc = $('.ui-toc');
        var tocAffix = $('.ui-affix-toc');
        var tocDropdown = $('.ui-toc-dropdown');
        //toc
        tocDropdown.click(function (e) {
            e.stopPropagation();
        });

        var enoughForAffixToc = true;

        function generateScrollspy() {
            $(document.body).scrollspy({
                target: ''
            });
            $(document.body).scrollspy('refresh');
            if (enoughForAffixToc) {
                toc.hide();
                tocAffix.show();
            } else {
                tocAffix.hide();
                toc.show();
            }
            $(document.body).scroll();
        }

        function windowResize() {
            //toc right
            var paddingRight = parseFloat(markdown.css('padding-right'));
            var right = ($(window).width() - (markdown.offset().left + markdown.outerWidth() - paddingRight));
            toc.css('right', right + 'px');
            //affix toc left
            var newbool;
            var rightMargin = (markdown.parent().outerWidth() - markdown.outerWidth()) / 2;
            //for ipad or wider device
            if (rightMargin >= 133) {
                newbool = true;
                var affixLeftMargin = (tocAffix.outerWidth() - tocAffix.width()) / 2;
                var left = markdown.offset().left + markdown.outerWidth() - affixLeftMargin;
                tocAffix.css('left', left + 'px');
            } else {
                newbool = false;
            }
            if (newbool != enoughForAffixToc) {
                enoughForAffixToc = newbool;
                generateScrollspy();
            }
        }
        $(window).resize(function () {
            windowResize();
        });
        $(document).ready(function () {
            windowResize();
            generateScrollspy();
        });

        //remove hash
        function removeHash() {
            window.location.hash = '';
        }

        var backtotop = $('.back-to-top');
        var gotobottom = $('.go-to-bottom');

        backtotop.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            if (scrollToTop)
                scrollToTop();
            removeHash();
        });
        gotobottom.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            if (scrollToBottom)
                scrollToBottom();
            removeHash();
        });

        var toggle = $('.expand-toggle');
        var tocExpand = false;

        checkExpandToggle();
        toggle.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            tocExpand = !tocExpand;
            checkExpandToggle();
        })

        function checkExpandToggle () {
            var toc = $('.ui-toc-dropdown .toc');
            var toggle = $('.expand-toggle');
            if (!tocExpand) {
                toc.removeClass('expand');
                toggle.text('Expand all');
            } else {
                toc.addClass('expand');
                toggle.text('Collapse all');
            }
        }

        function scrollToTop() {
            $('body, html').stop(true, true).animate({
                scrollTop: 0
            }, 100, "linear");
        }

        function scrollToBottom() {
            $('body, html').stop(true, true).animate({
                scrollTop: $(document.body)[0].scrollHeight
            }, 100, "linear");
        }
    </script>
</body>

</html>
