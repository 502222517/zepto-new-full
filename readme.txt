修改 zepto 源码 make 文件，添加所有模块

modules = (env['MODULES'] || my_modules || 'zepto event ajax form ie').split(' ')

my_modules = 'zepto event ajax form ie detect fx fx_methods assets data deferred callbacks selector touch gesture stack ios3'


