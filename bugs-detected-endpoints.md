# Bugs Detected Endpoints

* while deleting post, I detected SQLi bug in post id in url. ( POST post/647' gives 500 error | post/647--%20' give intended response)
* Open Redirect bug Or SSRF while registration https://8325c26354bf-yunus.a.barker-social.com/go?target=https://8325c26354bf-yunus.a.barker-social.com.yunus.com (can be redirected to our subdomain)
* editing group name has XSS bug
* under group there is a tagline which is vulnerable to xss
