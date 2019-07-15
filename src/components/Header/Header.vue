<template>
  <header class="header-section section sticker">
    <div class="container">
      <div class="row">
        <div class="col-xs-12">
          <!-- logo -->
          <div class="header-logo float-left">
            <a href>
              <img src alt="main logo" />
            </a>
          </div>
          <!-- header-search & total-cart -->
          <div class="float-right">
            <div class="header-option-btns float-right">
              <!-- header-search -->
              <div class="header-search float-left">
                <button class="search-toggle" data-toggle="dropdown">
                  <i class="pe-7s-search"></i>
                </button>
                <div class="dropdown-menu header-search-form">
                  <form action="#">
                    <input type="text" placeholder="Search" />
                    <button>
                      <i class="fa fa-long-arrow-right"></i>
                    </button>
                  </form>
                </div>
              </div>
              <!-- header Account -->
              <div class="header-account float-left">
                <ul>
                  <li>
                    <a href data-toggle="dropdown">
                      <i class="pe-7s-config"></i>
                    </a>
                    <ul class="dropdown-menu">
                      <li>
                        <a href="login.html">Log in</a>
                      </li>
                      <li>
                        <a href="register.html">Register</a>
                      </li>
                      <li>
                        <a href>My Account</a>
                      </li>
                      <li>
                        <a href="wishlist.html">Wish list</a>
                      </li>
                      <li>
                        <a href="checkout.html">Checkout</a>
                      </li>
                    </ul>
                  </li>
                </ul>
              </div>
              <!-- Header Cart -->
              <div class="header-cart float-left">
                <!-- Cart Toggle -->
                <a class="cart-toggle" href data-toggle="dropdown">
                  <i class="pe-7s-cart"></i>
                  <span>2</span>
                </a>
                <!-- Mini Cart Brief -->
                <div class="mini-cart-brief dropdown-menu text-left">
                  <!-- Cart Products -->
                  <div class="all-cart-product clearfix">
                    <div class="single-cart clearfix">
                      <div class="cart-image">
                        <a href="product-details.html">
                          <img src="img/product/cart-1.jpg" alt />
                        </a>
                      </div>
                      <div class="cart-info">
                        <h5>
                          <a href="product-details.html">Le Parc Minotti Chair</a>
                        </h5>
                        <p>1 x £9.00</p>
                        <a href class="cart-delete" title="Remove this item">
                          <i class="pe-7s-trash"></i>
                        </a>
                      </div>
                    </div>
                    <div class="single-cart clearfix">
                      <div class="cart-image">
                        <a href="product-details.html">
                          <img src="img/product/cart-2.jpg" alt />
                        </a>
                      </div>
                      <div class="cart-info">
                        <h5>
                          <a href="product-details.html">DSR Eiffel chair</a>
                        </h5>
                        <p>1 x £9.00</p>
                        <a href class="cart-delete" title="Remove this item">
                          <i class="pe-7s-trash"></i>
                        </a>
                      </div>
                    </div>
                  </div>
                  <!-- Cart Total -->
                  <div class="cart-totals">
                    <h5>
                      Total
                      <span>£12.00</span>
                    </h5>
                  </div>
                  <!-- Cart Button -->
                  <div class="cart-bottom clearfix">
                    <a href="checkout.html">Check out</a>
                  </div>
                </div>
              </div>
            </div>
            <nav class="main-menu menu-right float-right">
              <ul>
                <li class="active">
                  <a href>Home</a>
                  <ul class="sub-menu">
                    <li class="active">
                      <a href>Home one</a>
                    </li>
                    <li>
                      <a href="index-2.html">Home two</a>
                    </li>
                    <li>
                      <a href="index-3.html">Home three</a>
                    </li>
                  </ul>
                </li>
                <li>
                  <a href="shop.html">shop</a>
                  <ul class="sub-menu">
                    <li>
                      <a href="shop.html">shop</a>
                    </li>
                    <li>
                      <a href="product-details.html">product details</a>
                    </li>
                  </ul>
                </li>
                <li>
                  <a href>Pages</a>
                  <ul class="sub-menu">
                    <li>
                      <a href="cart.html">cart</a>
                    </li>
                    <li>
                      <a href="checkout.html">checkout</a>
                    </li>
                    <li>
                      <a href="login.html">login</a>
                    </li>
                    <li>
                      <a href="register.html">register</a>
                    </li>
                    <li>
                      <a href="wishlist.html">wishlist</a>
                    </li>
                  </ul>
                </li>
                <li>
                  <a href="blog.html">Blog</a>
                  <ul class="sub-menu">
                    <li>
                      <a href="blog.html">blog</a>
                    </li>
                    <li>
                      <a href="blog-details.html">blog details</a>
                    </li>
                  </ul>
                </li>
                <li>
                  <a href="contact.html">Contact</a>
                </li>
              </ul>
            </nav>
          </div>
          <div class="mobile-menu"></div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
//这里可以导入其他文件（比如：组件，工具js，第三方插件js，json文件，图片文件等等）
//例如：import 《组件名称》 from '《组件路径》';

export default {
  //import引入的组件需要注入到对象中才能使用
  components: {},
  data() {
    //这里存放数据
    return {}
  },
  //监听属性 类似于data概念
  computed: {},

  //方法集合
  methods: {},
  //生命周期 - 创建完成（可以访问当前this实例）
  created() {},
  //生命周期 - 挂载完成（可以访问DOM元素）
  mounted() {}
}
</script>

    <style lang="css" src="@/assets/css/bootstrap.min.css"></style>
  <style lang="css" src="@/assets/css/font-awesome.min.css"></style>  
    <style lang="css" src="@/assets/css/pe-icon-7-stroke.css"></style>  
   <style lang="css" src="@/assets/css/style.css"></style>  
     <style lang="css" src="@/assets/css/responsive.css"></style>    

<style lang="css">
 @import '../../assets/css/bootstrap.min.css';
</style>  