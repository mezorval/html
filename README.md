<!DOCTYPE html>
<html>
<head>
  <title>Widget Example</title>
</head>
<body>
  <script>
    !function(e){
      var l=function(l){return e.cookie.match(new RegExp("(?:^|; )digiseller-"+l+"=([^;]*)"))},
      i=l("lang"),s=l("cart_uid"),t=i?"&lang="+i[1]:"",d=s?"&cart_uid="+s[1]:"",
      r=e.getElementsByTagName("head")[0]||e.documentElement,n=e.createElement("link"),a=e.createElement("script");
      n.type="text/css",n.rel="stylesheet",n.id="digiseller-css",n.href="//shop.digiseller.ru/xml/store2_css.asp?seller_id=1138592",
      a.async=!0,a.id="digiseller-js",a.src="//www.digiseller.ru/store2/digiseller-api.js.asp?seller_id=1138592"+t+d,
      !e.getElementById(n.id)&&r.appendChild(n),!e.getElementById(a.id)&&r.appendChild(a)
    }(document);
  </script>

  <div style="display: inline-block;" class="digiseller-buy-standalone" data-id="3422605" data-ai="1138592" data-img="1" data-img-size="180" data-name="1" data-price="1" data-no-price="0"></div>
</body>
</html>
