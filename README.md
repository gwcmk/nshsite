###portfolio-2
Changelog:
* Used #CE4115 as primary color in button and h2 border. Also used #3A3A3C in .portfolio-item-overlay
* Updated "Learn More" buttons with links to websites and used target="_blank"
* **Disabled one line in elements.css (selector: .portfolio-item-2:hover .portfolio-item-overlay)**
* Added some hacky CSS to vertically center images

TODO:
* Get high res images
```
<style type="text/css">
.portfolio-item-2 .portfolio-item-description h2 span{
    border-left: 2px solid #CE4115;
}
.btn:hover {
    border-color: #CE4115!important;
    color: #CE4115!important;
}
.portfolio-item-overlay{
    background-color: #3A3A3C;
}
.portfolio-item-2{
    border: 0px!important;
}
.portfolio-item-2:hover{
    opacity: 1;
} 
.portfolio-item-overlay:hover { opacity: 0.9!important; }
.portfolio-item-preview{
    height: 100%;
    overflow: hidden;
}
.portfolio-item-preview > img{
    max-height: 100%;
    position: relative;
    top: 50%;
    transform: translateY(-50%);
    padding: 0px;
    vertical-align: middle;
}

@media (max-width: 767px) {
    .portfolio-item-2 .portfolio-item-description h2 span{
        border-left: 0;
    }
    .portfolio-item-2 .portfolio-item-description h2 span:before{
        border-top: 0;
    }
    .portfolio-item-2 .portfolio-item-description h2 span{
        border-bottom: 2px solid #CE4115;
    }
    .portfolio-item-preview > img{
        position: relative;
        top: 0;
        padding: 0;
        transform: translateY(0);
    }

}
</style>
```

###Apply page
