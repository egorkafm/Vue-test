<template>
  <div class="container">
    <div class="profile">
      <div class="profile__header"> 
        <div class="profile__logo"><img src="../public/img/logo.svg" alt="logo"/></div>
        <div class="profile__links">
          <a class="profile__links" href="/">Home</a>
            <span>
              <img src="../public/img/Vector2.svg" alt="altText"/>
            </span>
            <a class="profile__links" href="https://www.google.com.ua/?hl=ru" target="_blank">Search</a>
            <span>
              <img src="../public/img/Vector2.svg" alt="altText"/>
            </span>
            <a class="profile__links" href="https://www.google.com.ua/?hl=ru">Results</a></div>
        <div> 
          <button class="profile__btn">Sarah Freeman</button>
        </div>
      </div>
      <div class="profile__content"> 
        <div class="profile__nav">
          <nav> 
            <ul> 
              <li class="profile__nav-active">
                <svg class="svg" width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path class="svg" fill-rule="evenodd" clip-rule="evenodd" d="M17.5595 15.4322L13.6491 11.5219C13.6283 11.5011 13.6039 11.4866 13.5822 11.4672C14.3516 10.3001 14.8007 8.90292 14.8007 7.40043C14.8007 3.31327 11.4874 0 7.40036 0C3.31327 0 0 3.31327 0 7.40036C0 11.4874 3.31319 14.8007 7.40028 14.8007C8.90285 14.8007 10.2999 14.3516 11.4671 13.5822C11.4864 13.6038 11.5009 13.6282 11.5217 13.649L15.4322 17.5595C16.0196 18.1468 16.972 18.1468 17.5595 17.5595C18.1468 16.972 18.1468 16.0197 17.5595 15.4322ZM7.40036 12.2352C4.73004 12.2352 2.5654 10.0706 2.5654 7.40036C2.5654 4.73004 4.73011 2.5654 7.40036 2.5654C10.0705 2.5654 12.2352 4.73011 12.2352 7.40036C12.2352 10.0706 10.0705 12.2352 7.40036 12.2352Z" fill="#8089A6"/>
                </svg>
              </li>
              <li>
                <svg class="svg" width="18" height="19" viewBox="0 0 18 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M9.00024 9.59594C11.229 9.59594 13.0361 7.4478 13.0361 4.79795C13.0361 1.12334 11.2291 0 9.00024 0C6.77125 0 4.96442 1.12334 4.96442 4.79795C4.96446 7.4478 6.7713 9.59594 9.00024 9.59594Z" fill="white"/>
                <path d="M17.912 16.6586L15.8758 11.9998C15.7827 11.7866 15.6191 11.6098 15.4155 11.5021L12.2555 9.83135C12.1858 9.79458 12.1015 9.80173 12.0388 9.8499C11.1451 10.5365 10.0942 10.8994 9.00004 10.8994C7.90565 10.8994 6.8549 10.5365 5.96116 9.8499C5.89834 9.80173 5.81396 9.79458 5.74428 9.83135L2.58455 11.5021C2.38083 11.6098 2.2174 11.7866 2.12418 11.9998L0.088054 16.6586C-0.0523244 16.9798 -0.0235536 17.3473 0.16504 17.6419C0.353546 17.9364 0.672575 18.1122 1.01848 18.1122H16.9815C17.3274 18.1122 17.6465 17.9363 17.835 17.6418C18.0235 17.3473 18.0524 16.9797 17.912 16.6586Z" fill="white"/>
                </svg>
              </li>
              <li>
                <svg class="svg" width="20" height="17" viewBox="0 0 20 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path id="gg" d="M1.9196 5.31729C2.1726 5.49863 2.93522 6.03719 4.20752 6.9327C5.47985 7.82821 6.45455 8.51773 7.13164 9.0013C7.20603 9.05431 7.36408 9.16953 7.60585 9.34713C7.84767 9.52485 8.0486 9.66847 8.20848 9.77801C8.36848 9.88752 8.5619 10.0104 8.78894 10.1464C9.0159 10.2822 9.22985 10.3844 9.43074 10.4521C9.63167 10.5203 9.81766 10.5541 9.98876 10.5541H9.99998H10.0112C10.1823 10.5541 10.3684 10.5203 10.5693 10.4521C10.7702 10.3844 10.9843 10.2821 11.2111 10.1464C11.4379 10.0102 11.6314 9.88748 11.7914 9.77801C11.9514 9.66847 12.1521 9.52485 12.394 9.34713C12.6358 9.16937 12.794 9.05431 12.8684 9.0013C13.5528 8.51773 15.294 7.28961 18.0915 5.31705C18.6347 4.93179 19.0884 4.46693 19.453 3.92277C19.8178 3.37885 20 2.80824 20 2.21127C20 1.71242 19.8232 1.28539 19.4697 0.930225C19.1163 0.574983 18.6977 0.397461 18.2142 0.397461H1.78564C1.21276 0.397461 0.771891 0.593922 0.463111 0.986845C0.15437 1.37985 0 1.87108 0 2.4605C0 2.93661 0.20468 3.45254 0.613846 4.00797C1.02297 4.56345 1.45837 4.99993 1.9196 5.31729Z" fill="white" fill-opacity="0.5"/>
                <path id="gg" d="M18.8838 6.5299C16.4435 8.20748 14.5906 9.51124 13.3259 10.4409C12.9018 10.7582 12.5578 11.0059 12.2936 11.1833C12.0294 11.3609 11.678 11.5423 11.2389 11.7274C10.8 11.9127 10.3909 12.0051 10.0114 12.0051H10H9.9888C9.60934 12.0051 9.20006 11.9127 8.76115 11.7274C8.32224 11.5423 7.97061 11.3609 7.70647 11.1833C7.44241 11.0059 7.09826 10.7582 6.6742 10.4409C5.66968 9.69278 3.82075 8.38894 1.12734 6.5299C0.703129 6.24291 0.327387 5.91395 0 5.5437V14.5443C0 15.0434 0.174776 15.4702 0.524523 15.8254C0.874192 16.1807 1.29465 16.3583 1.78575 16.3583H18.2144C18.7053 16.3583 19.1258 16.1807 19.4755 15.8254C19.8253 15.47 20 15.0434 20 14.5443V5.5437C19.68 5.90629 19.3081 6.23525 18.8838 6.5299Z" fill="white" fill-opacity="0.5"/>
                </svg>
              </li>
              <li>
                <svg class="svg" width="20" height="21" viewBox="0 0 20 21" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M14.9792 4.34873C15.7576 4.34873 16.388 3.72254 16.388 2.94421V1.47277C16.388 0.693732 15.7576 0.0654297 14.9792 0.0654297C14.2016 0.0654297 13.5733 0.693732 13.5733 1.47277V2.94421C13.5733 3.72254 14.2016 4.34873 14.9792 4.34873Z" fill="white" fill-opacity="0.5"/>
                <path d="M19.9796 2.50064H17.1473V3.21699C17.1473 4.39752 16.1872 5.3604 15.0039 5.3604C13.8191 5.3604 12.8619 4.39752 12.8619 3.21699V2.50064H7.14447V3.21699C7.14447 4.39752 6.18441 5.3604 5.00106 5.3604C3.81771 5.3604 2.85905 4.39682 2.85905 3.21629V2.50064L1.59539e-09 2.46472V20.3572H1.42918H18.5736L20 20.353L19.9796 2.50064ZM18.5736 18.9323H1.42918V7.5017H18.5736V18.9323Z" fill="white" fill-opacity="0.5"/>
                <path d="M4.97838 4.34873C5.75671 4.34873 6.38572 3.72254 6.38572 2.94421V1.47277C6.38572 0.693732 5.75742 0.0654297 4.97838 0.0654297C4.20145 0.0654297 3.57245 0.693732 3.57245 1.47277V2.94421C3.57245 3.72254 4.20145 4.34873 4.97838 4.34873Z" fill="white" fill-opacity="0.5"/>
                <path d="M9.39983 9.03589H7.14935V11.0229H9.39983V9.03589Z" fill="white" fill-opacity="0.5"/>
                <path d="M5.87792 9.03589H3.62744V11.0229H5.87792V9.03589Z" fill="white" fill-opacity="0.5"/>
                <path d="M13.0428 9.03589H10.7895V11.0229H13.0428V9.03589Z" fill="white" fill-opacity="0.5"/>
                <path d="M16.416 9.03589H14.1655V11.0229H16.416V9.03589Z" fill="white" fill-opacity="0.5"/>
                <path d="M9.39983 12.3356H7.14935V14.3212H9.39983V12.3356Z" fill="white" fill-opacity="0.5"/>
                <path d="M13.0428 12.3356H10.7895V14.3212H13.0428V12.3356Z" fill="white" fill-opacity="0.5"/>
                <path d="M16.416 12.3356H14.1655V14.3212H16.416V12.3356Z" fill="white" fill-opacity="0.5"/>
                <path d="M9.39983 15.7013H7.14935V17.6869H9.39983V15.7013Z" fill="white" fill-opacity="0.5"/>
                <path d="M5.82152 12.3356H3.57245V14.3212H5.82152V12.3356Z" fill="white" fill-opacity="0.5"/>
                <path d="M5.82152 15.7013H3.57245V17.6869H5.82152V15.7013Z" fill="white" fill-opacity="0.5"/>
                <path d="M13.0428 15.7013H10.7895V17.6869H13.0428V15.7013Z" fill="white" fill-opacity="0.5"/>
                <path d="M16.416 15.7013H14.1655V17.6869H16.416V15.7013Z" fill="white" fill-opacity="0.5"/>
                </svg>
              </li>
            </ul>
          </nav>
        </div>
        <div class="profile__item"> 
          <div class="search">
            <div class="search__form">
              <form action="#" method="POST">
                <div> 
                  <label>LOCATION</label><br/>
                  <select class="profile__imp profile__imp-location">
                    <option style="display:none;"></option>
                    <option value="TR">TR	</option>
                    <option value="UA">UA </option>
                    <option value="US">US</option>
                    <option value="JP">JP</option>
                  </select>
                </div>
                <div> 
                  <label>SEARCH</label><br/>
                  <input class="profile__imp" type="text" placeholder="Type your query..."/>
                </div>
                <div> 
                  <label>CATEGORY </label><br/>
                  <select class="profile__imp">
                    <option value="Category">Category</option>
                    <option value="Category2">Category 2</option>
                    <option value="Category3">Category 3</option>
                    <option value="Category4">Category 4</option>
                  </select>
                </div>
                <div> 
                  <label>SERVICE </label><br/>
                  <select class="profile__imp">
                    <option value="3 services">3 services</option>
                    <option value="4 services">4 services</option>
                    <option value="5 services">5 services</option>
                    <option value="6 services">6 services</option>
                  </select>
                </div>
                <div> 
                  <label>PERIOD </label><br/>
                  <form action="#" method="POST"></form>
                  <input class="profile__imp" type="date" name="calendar" value="2020-03-21"/>
                </div>
                <button class="search__form-btn">SEARCH</button>
              </form>
            </div>
            <div class="search__info">
              <div class="search__info-header"> 
                <button class="search__info-btn">SHOW MAP</button>
                <div> 
                  <img src="../public/img/Group2.svg" alt="altText"/>
                  <form action="#" method="POST">
                    <input class="custom-radio" name="radio1" type="radio" id="radio1" value="by price"/>
                    <label for="radio1">by price &nbsp;</label>
                    <input class="custom-radio" name="radio2" type="radio" id="radio2" value="by rating"/>
                    <label for="radio2">by rating</label>
                  </form>
                </div>
              </div>
              <div class="search__info-contetnt">
                <div class="search__info-card"> 
                  <div class="search__card-photo"><img src="../public/img/MaskGroup.svg" alt="photo"/></div>
                  <div class="search__card-title"> 
                    <p class="search__card-title-gold">Richard Thompson </p>
                    <div class="search__card-location">Vancouver, Canada</div>
                    <div class="search__card-stack"> <span>Stack: </span><span>Python, Django, Sketch </span><a href="#">More</a></div>
                    <div class="search__card-salary"> <span>Base Daily Rate: </span><span>$ 1,200 USD</span></div>
                  </div>
                </div>
                <div class="search__info-card"> 
                  <div class="search__card-photo"><img src="../public/img/MaskGroup2.svg" alt="photo"/></div>
                  <div class="search__card-title">
                    <p class="search__card-title-gold">Richard Thompson </p>
                    <div class="search__card-location">Vancouver, Canada</div>
                    <div class="search__card-stack"> <span>Stack: </span><span>Python, Django, Sketch </span><a href="#">More</a></div>
                    <div class="search__card-salary"> <span>Base Daily Rate: </span><span>$ 1,200 USD</span></div>
                  </div>
                </div>
                <div class="search__info-card"> 
                  <div class="search__card-photo"><img src="../public/img/MaskGroup3.svg" alt="photo"/></div>
                  <div class="search__card-title"> 
                    <p class="search__card-title-bronze">Richard Thompson </p>
                    <div class="search__card-location">Vancouver, Canada</div>
                    <div class="search__card-stack"> <span>Stack: </span><span>NodeJs, AngularJs</span><a href="#">More</a></div>
                    <div class="search__card-salary"> <span>Base Daily Rate: </span><span>$ 1,200 USD</span></div>
                  </div>
                </div>
                <div class="search__info-card"> 
                  <div class="search__card-photo"><img src="../public/img/MaskGroup4.svg" alt="photo"/></div>
                  <div class="search__card-title">
                    <p class="search__card-title">Richard Thompson </p>
                    <div class="search__card-location">Vancouver, Canada</div>
                    <div class="search__card-stack"> <span>Stack: </span><span>VueJs, React Native, QA</span></div>
                    <div class="search__card-salary"> <span>Base Daily Rate: </span><span>$ 1,200 USD</span></div>
                  </div>
                </div>
                <div class="search__info-card"> 
                  <div class="search__card-photo"><img src="../public/img/MaskGroup5.svg" alt="photo"/></div>
                  <div class="search__card-title"> 
                    <p class="search__card-title-gold">Richard Thompson </p>
                    <div class="search__card-location">Vancouver, Canada</div>
                    <div class="search__card-stack"> <span>Stack: </span><span>Php, Smesitel</span><a href="#">More</a></div>
                    <div class="search__card-salary"> <span>Base Daily Rate: </span><span>$ 1,200 USD</span></div>
                  </div>
                </div>
                <div class="search__info-card"> 
                  <div class="search__card-photo"><img src="../public/img/MaskGroup5.svg" alt="photo"/></div>
                  <div class="search__card-title">
                    <p class="search__card-title-silver">Richard Thompson </p>
                    <div class="search__card-location">Vancouver, Canada</div>
                    <div class="search__card-stack"> <span>Stack: </span><span>React, jQuery</span></div>
                    <div class="search__card-salary"> <span>Base Daily Rate: </span><span>$ 1,200 USD</span></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import apiService from '../helpers/api';

export default {
  name: 'SearchResults',
  // components: {
  //   CustomButton,
  // },
  data() {
    return { SearchResults: [] }
  },

  beforeCreate() {
    apiService.get('/SearchResults')
      .then((res) => {
        console.log(res);
        this.SearchResults = res.data.SearchResults
      })
      .catch((err) => {
        console.log(err);
      })
  }
}
</script>

<style>
.search {
  display: flex;
  width: 86vw;
  padding: 20px;
}
@media (max-width: 768px) {
  .search {
    padding: 10px;
  }
}
@media (max-width: 460px) {
  .search {
    flex-wrap: wrap;
    padding: 5px;
  }
}
.search__form {
  flex: 25%;
}
@media (max-width: 460px) {
  .search__form {
    flex: 100%;
  }
}
.search__form form {
  display: block;
}
.search__form div {
  max-width: 90%;
  margin: 0 auto;
}
.search__form-btn {
  display: block;
  min-width: 90%;
  margin: 0 auto;
  height: 40px;
  background-color: #0ad69c;
  border: none;
  border-radius: 2px;
  color: #fff;
  text-align: center;
  text-decoration: none;
  font-weight: 600;
  font-size: 16px;
  line-height: 19px;
  letter-spacing: 0.4px;
  transition-duration: 0.4s;
  cursor: pointer;
}
.search__form-btn:hover {
  background-color: #fff;
  outline: solid 1px #0ad69c;
  color: #222428;
}
.search__info {
  flex: 70%;
  margin-left: 45px;
  border: 1px solid transparent;
  -o-border-image: url("../public/img/Line3.4.svg") 0 0 0 30 round;
  border-image: url("../public/img/Line3.4.svg") 0 0 0 30 round;
}
@media (max-width: 960px) {
  .search__info {
    margin: 0 auto;
  }
}
@media (max-width: 460px) {
  .search__info {
    margin: 0 auto;
    -o-border-image: none;
    border-image: none;
  }
}
.search__info-header {
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-between;
  align-items: center;
}
.search__info-header form {
  display: inline-block;
  vertical-align: middle;
}
.search__info-header img {
  margin-right: 20px;
}
.search__info-btn {
  color: #01134e;
  background-color: #fff;
  margin: 0 15px 0 20px;
  outline: 0;
  border: none;
  font-size: 12px;
  line-height: 14px;
  display: block;
  white-space: nowrap;
  padding: 20px 0;
}
.search__info-btn:hover {
  cursor: pointer;
}
.search__info-contetnt {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  flex: 50%;
  padding: 50px;
}
@media (max-width: 960px) {
  .search__info-contetnt {
    padding: 20px;
  }
}
.search__info-card {
  display: flex;
  flex: 45%;
  background-color: #fff;
  box-shadow: -2px 9px 30px rgba(23, 31, 76, 0.02);
  margin: 20px 10px;
}
@media (max-width: 768px) {
  .search__info-card {
    flex: 100%;
    margin: 10px;
  }
}
@media (max-width: 460px) {
  .search__info-card {
    justify-content: center;
  }
}
.search__card-title {
  color: #01134e;
  font-size: 12px;
  line-height: 12px;
}
.search__card-title p {
  font-size: 16px;
  line-height: 28px;
}
.search__card-title-gold::after {
  content: url(../public/img/gold.svg);
  vertical-align: middle;
}
.search__card-title-silver::after {
  content: url(../public/img/silver.svg);
  vertical-align: middle;
}
.search__card-title-bronze::after {
  content: url(../public/img/bronze.svg);
  vertical-align: middle;
}
.search__card-location {
  font-size: 12px;
  line-height: 12px;
}
.search__card-location::before {
  margin-right: 5px;
  content: url(../public/img/Location.svg);
  vertical-align: middle;
}
.search__card-stack {
  font-size: 12px;
  line-height: 24px;
}
.search__card-stack span:nth-child(1) {
  color: #01134e;
  font-weight: 700;
}
.search__card-salary span:nth-child(1) {
  color: #01134e;
  font-weight: 700;
}
@media (max-width: 460px) {
  .search__map {
    display: block;
    margin: 0 auto;
    width: 100%;
    height: 300px;
  }
}
.custom-radio {
  position: absolute;
  z-index: -1;
  opacity: 0;
}
.custom-radio + label {
  display: inline-flex;
  align-items: center;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.custom-radio + label::before {
  content: "";
  display: inline-block;
  width: 1em;
  height: 1em;
  flex-shrink: 0;
  flex-grow: 0;
  border: 1px solid #adb5bd;
  border-radius: 50%;
  margin-right: 0.5em;
  background-repeat: no-repeat;
  background-position: center center;
  background-size: 50% 50%;
}
.custom-radio:not(:disabled):not(:checked) + label:hover::before {
  border-color: #b3d7ff;
}
.custom-radio:not(:disabled):active + label::before {
  background-color: #b3d7ff;
  border-color: #b3d7ff;
}
.custom-radio:focus + label::before {
  box-shadow: 0 0 0 0.2rem rgba(212, 206, 202, 0.58);
}
.custom-radio:focus:not(:checked) + label::before {
  border-color: #80bdff;
}
.custom-radio:checked + label::before {
  border-color: #f0f1f3;
  background-color: #f0f1f3;
  box-shadow: rgba(212, 206, 202, 0.58);
  background-image: url("../public/img/Ellipse3.svg");
  background-position: center;
}
.custom-radio:disabled + label::before {
  background-color: #e9ecef;
}
</style>