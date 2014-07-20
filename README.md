# jquery-fullscreen [![spm version](http://spmjs.io/badge/jquery-fullscreen)](http://spmjs.io/package/jquery-fullscreen)

AUTHOR WEBSITE: [http://ydr.me/](http://ydr.me/)

jquery.fn.fullscreen 全屏插件

**五星提示：当前脚本未作优化、未完工，请勿用在生产环境**

__IT IS [A SPM PACKAGE](http://spmjs.io/package/jquery-fullscreen).__




#USAGE
```
var $ = require('jquery');
require('jquery-fullscreen')($);

$("#demo").fullscreen({...});
```



#OPTIONS
```
$.fn.fullscreen.defaults = {
    // 自动打开全屏
    autoOpen: true,
    // 打开全屏回调
    onopen: function() {},
    // 关闭全屏回调
    onclose: function() {}
};
```
