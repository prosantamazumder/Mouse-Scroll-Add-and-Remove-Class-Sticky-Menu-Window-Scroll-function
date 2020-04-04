# Mouse Scroll Add and Remove Class Sticky Menu Window Scroll function

**Live Demo**
[repositories.presstechit-institute.com](http://repositories.presstechit-institute.com/Scroll-add-And-Remove-Class/)




### ISOTOP FILTERING HTML Markup 

```
  <!-- sticky Section  -->
  <div class="<strong>stickySection </strong>">
      <div class="container">
          <div class="row">
              <div class="col-lg-6 offset-lg-3">
                  <div class="prevention-area-header-title text-center mb-40">
                      <h4>Important Prevention</h4>
                      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed quis accumsan nisi Ut ut felis congue nisl hendrerit commodo.</p>
                  </div>
              </div>
          </div>
      </div>
  </div>
  <!-- End sticky Section  -->
```


### HEADER STICKY AREA JS CODE active.js

```
	$(window).on('scroll',function() {
		if ($(this).scrollTop() > 0){  
	    	$('.stickySection').addClass("sticky");
	  	}else{
	    	$('.stickySection').removeClass("sticky");
	  	}
	});
```


### ADD CLASS SOME PIXIEL SCROLL PLUGINS.js

```
	$(window).scroll(function() {    
	    var scroll = $(window).scrollTop();

	    if (scroll >= 500) {
	        $(".clearHeader").addClass("redHeader");
	    } else {
	        $(".clearHeader").removeClass("redHeader");
	    }
	});
```

### Ask Any Question or if you need help contact me 24/7 we are ready support team.

[Facebook:](https://www.facebook.com/PMPROSANTA0)<br />
[Web:](http://presstechit-institute.com/)\
[Personal:](http://pm-prosanto.themefusions.com/)\
[Email Me:](mailto:prosantomazumder@gmail.com)\
[Linkedin:](https://www.linkedin.com/in/prosantomazumder/)\
[Twitter:](https://twitter.com/prosantomazumd1)\
[Instagram:](https://www.instagram.com/prosantomazumder/)\
[Codepen:](https://codepen.io/ProsantaMazumder)


### Changelog
- [x] Version 1.0.3

##### Cradit
[Bootstrap](https://getbootstrap.com/)
[FontAwesome](https://fontawesome.com/v4.7.0/)
