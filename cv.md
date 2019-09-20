# Resume

1. ### Kirill Malakha
2. ### Contacts:
* Telegram: @wergosha;
* vk: id360540819;
* tel: +7 (901) 161 38 25;
3. I'm beginner in Front-end development and I want to improve my skills.

4. ### Skills:
* HTML5/CSS3 - novice;
* JS - going to learn;
* React - going to learn;
* Python - novice.
5. ### Code example:
```javascript
$(document).ready(function(){
    var headerSlider = $('#headerSlider');

    headerSlider.on('initialized.owl.carousel', function(event){
        $('.slider-control__number-active').text(event.item.index + 1)
        $('.slider-control__number-total').text(event.item.count)
    });

    headerSlider.owlCarousel({
        items: 1,
        //loop: true,
        dots: false,
        smartSpeed: 1000,
    }); 
    $('#headerSliderRight').click(function() {
        headerSlider.trigger('next.owl.carousel');
    })
    $('#headerSliderLeft').click(function() {
        headerSlider.trigger('prev.owl.carousel');
    })
    headerSlider.on('changed.owl.carousel', function(event){
        $('.slider-control__number-active').text(event.item.index + 1)
        $('.slider-control__number-total').text(event.item.count)
    });
});
```
6. I try to develop a simple landing page websites 
* [Surf club](http://wergosha.github.io/surfclub)
* [Skinali](http://wergosha.github.io/skinali)

7. I have done basic courses of HTML/CSS on the HTMLAcademy. Also watching education YouTube channels like: [GloAcademy](https://www.youtube.com/channel/UCVswRUcKC-M35RzgPRv8qUg), [IT-KAMASUTRA](https://www.youtube.com/channel/UCTW0FUhT0m-Bqg2trTbSs0g), [DevEd](https://www.youtube.com/channel/UClb90NQQcskPUGDIXsQEz5Q), [WebCademy](https://www.youtube.com/channel/UCBB1kqYMWUrSxrQkq8BYzZA)
8. I studied English at school. For now I use English in a buiseness case to speak with customers from China and Europe. But I really don't know what level of English I have. 
In this time we have an online translaters which help to speak/write in not native language. I can read technical documentation in English.
