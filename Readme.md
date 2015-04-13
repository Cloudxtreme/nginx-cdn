# Build CDN with Openresty 



Đây là các mã nguồn Nginx + Lua được tôi sử dụng trong dự án triển khai CDN. Danh sách này được tôi phân phối lại từ [Roman Heinrich](https://github.com/mindreframer/nginx-lua-stuff). Nginx + Lua có khả năng xử lý tốt hơn hẳn về hiệu suất xử lý so với một số nền tảng khác như node.js, PHP....Một số vấn đề trong triển khai CDN được tôi đề cập tại [blog cá nhân](http://swpag.info/content-delivery-network.html).

Blog cá nhân: http://swpag.info/


## Một số bài viết mà có thể bạn quan tâm:
  - http://3scale.github.io/2013/04/18/accelerate-your-mobile-api-with-nginx-and-lua/
  - http://www.slideshare.net/mizzy/inside-sqales-backend-at-yapcasia-tokyo-2012 (!!!)
  - http://www.textrazor.com/blog/2013/03/scaling-textrazor-in-the-cloud-with-nginx-and-lua.html
  - http://3scale.github.com/2013/01/09/augment-your-api-without-touching-it/
  - http://blog.cloudflare.com/pushing-nginx-to-its-limit-with-lua
  - http://seatgeek.com/blog/dev/oauth-support-for-nginx-with-lua
  - http://mikeferrier.com/2011/05/14/my-beautiful-dark-twisted-reverse-proxy-LRU-cache/ (!!!)
  - http://www.nginx-discovery.com/2011/03/day-41-setting-up-ngxopenresty-was.html
  - http://www.londonlua.org/scripting_nginx_with_lua/slides.html?full
  - http://ntcn.net/blog/?p=4469 (High Performance Caching with Nginx, Redis & PHP)


## OpenResty:

  - http://openresty.org/
  - http://openresty.org/download/agentzh-nginx-tutorials-enuk.html (!!!)
  - https://github.com/agentzh/ngx_openresty
  - http://qa.openresty.org/
  - https://github.com/kindy/lj-web
  - http://agentzh.org/misc/slides/ngx-openresty-ecosystem/#1
  - http://agentzh.org/misc/slides/ngx-openresty-ecosystem.pdf
  - http://agentzh.org/misc/slides/libdrizzle-lua-nginx/#2
  - http://agentzh.org/misc/slides/libdrizzle-lua-nginx.pdf
  - http://agentzh.org/misc/slides/perl-lz-apps.pdf
  - http://agentzh.org/misc/slides/nginx-conf-scripting/
  - http://agentzh.org/misc/slides/nginx-conf-scripting.pdf
  - http://agentzh.org/misc/slides/nginx-state-of-the-art/
  - http://agentzh.org/misc/slides/taobao-fe-vdomwebkit.pdf


Một số hướng dẫn về Openresty:

  - https://github.com/37signals/intermission
  - https://github.com/samalba/hipache-nginx
  - https://github.com/shrikeh/csrf-nginx-redis-lua
  - https://github.com/irr/stock-labs
  - https://github.com/agentzh/mysql-driver-benchmark (with MySQL)
  - https://gist.github.com/justincormack/948423 (proxy to AWS, with crypto stuff)
  - https://github.com/torhve/Amatyr (Postgres + Webapp)


## Nginx cơ bản:
  - [Use Nginx to proxy files from remote location using X-Accel-Redirect, 2013.09](http://distinctplace.com/infrastructure/2013/09/18/use-nginx-to-proxy-files-from-remote-location-using-x-accel-redirect/)
  - [Настраиваем NGINX для мультиязычных сайтов](http://habrahabr.ru/company/ruvpn/blog/183060/)

## Danh sách các mã nguồn

- https://github.com/37signals/intermission.git
- https://github.com/agentzh/array-var-nginx-module.git
- https://github.com/agentzh/echo-nginx-module.git
- https://github.com/agentzh/encrypted-session-nginx-module.git
- https://github.com/agentzh/headers-more-nginx-module.git
- https://github.com/agentzh/lua-resty-core.git
- https://github.com/agentzh/lua-resty-memcached.git
- https://github.com/agentzh/lua-resty-mysql.git
- https://github.com/agentzh/lua-resty-redis.git
- https://github.com/agentzh/lua-resty-string.git
- https://github.com/agentzh/lua-resty-upload.git
- https://github.com/agentzh/lua-resty-websocket.git
- https://github.com/agentzh/memc-nginx-module.git
- https://github.com/agentzh/nginx-systemtap-toolkit.git
- https://github.com/agentzh/ngx_openresty.git
- https://github.com/agentzh/rds-csv-nginx-module.git
- https://github.com/agentzh/rds-json-nginx-module.git
- https://github.com/agentzh/redis2-nginx-module.git
- https://github.com/agentzh/replace-filter-nginx-module.git
- https://github.com/agentzh/srcache-nginx-module.git
- https://github.com/agentzh/test-nginx.git
- https://github.com/appwilldev/moochine-demo.git
- https://github.com/appwilldev/moochine.git
- https://github.com/bakins/lua-resty-riak.git
- https://github.com/bakins/omnibus-nginx.git
- https://github.com/bakins/stardust.git
- https://github.com/benagricola/openresty-squiz-util.git
- https://github.com/bigplum/lua-resty-mongol.git
- https://github.com/bsm/fakengx.git
- https://github.com/chaoslawful/drizzle-nginx-module.git
- https://github.com/chaoslawful/lua-nginx-module.git
- https://github.com/cloudaice/redis-restful.git
- https://github.com/cloudflare/lua-nginx-cache-module.git
- https://github.com/dererk/dt.git
- https://github.com/desbouis/nginx-redis-proxy.git
- https://github.com/devkato/nginx-bandit-lua.git
- https://github.com/fcambus/telize.git
- https://github.com/FTBpro/count-von-count.git
- https://github.com/garethr/nginx-json-proxy.git
- https://github.com/jtarchie/sinatra-openresty.git
- https://github.com/leafo/moonrocks-site.git
- https://github.com/liseen/lua-resty-http.git
- https://github.com/medcl/lua-resty-weedfs.git
- https://github.com/mindreframer/github-auth-nginx.git
- https://github.com/miurahr/lua-nginx-osm.git
- https://github.com/observing/balancerbattle.git
- https://github.com/Olivine-Labs/resty-mongol.git
- https://github.com/osmfj/tileman.git
- https://github.com/pgaertig/nginx-big-upload.git
- https://github.com/pintsized/ledge.git
- https://github.com/rebill/nginx-lua-in-action.git
- https://github.com/samalba/hipache-nginx.git
- https://github.com/seandong/ad-analytics.git
- https://github.com/solso/api-aggregator.git
- https://github.com/solso/insomnia.git
- https://github.com/thattommyhall/nginx-lua-examples.git
- https://github.com/torhve/Amatyr.git
- https://github.com/torhve/LuaWeb.git
- https://github.com/torhve/Nyfyk.git
- https://github.com/torhve/pix.git
- https://github.com/wstucco/ssga.lua.git
- https://github.com/xinqiyang/yagamiko.git
- https://github.com/yo2oneoo/lua-resty-httpclient.git
