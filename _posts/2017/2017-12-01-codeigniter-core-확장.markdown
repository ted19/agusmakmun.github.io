---
layout: "post"
title: "CodeIgniter Core 확장"
date: "2017-12-01 19:37"
categories: [codeigniter]
---

코어 확장 방법 :

#### 1. Controller 확장방법

application/core 디렉토리에 MY_Controller.php 파일을 만들고 아래와 같이 클래스를 만든다.

{% highlight php %}
<?php if ( ! defined('BASEPATH')) exit('No direct script access allowed');
class MY_Controller extends CI_Controller {
    function __construct() {
        parent::__construct();      
    }    
}
{% endhighlight %}

#### 2. Model 확장방법

application/core 디렉토리에 MY_Model.php 파일을 만들고 아래와 같이 클래스를 만든다.

{% highlight php %}
<?php if ( ! defined('BASEPATH')) exit('No direct script access allowed');
class MY_Model extends CI_Model {
    function __construct() {
        parent::__construct();      
    }    
}
{% endhighlight %}
