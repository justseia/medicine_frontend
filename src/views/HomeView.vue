<template>
    <div class="banner-area bg-1 ptb-100">
        <div class="container-fluid">
            <div class="row align-items-end">
                <div class="col-xl-7">
                    <div class="banner-content">
                        <span class="top-title wow fadeInUp delay-0-2s">Начните свое путешествие</span>
                        <h1 class="wow fadeInUp delay-0-4s">Мы предоставляем услуги дистанционной медицины</h1>
                        <div class="banner-btn wow fadeInUp delay-0-8s">
                            <RouterLink to="/prices" class="default-btn"> Начать </RouterLink>
                        </div>

                        <ul class="social wow fadeInUp delay-0-8s">
                            <li>
                                <span>Социальные сети</span>
                            </li>
                            <li>
                                <a href="https://facebook.com/" target="_blank">
                                    <i class="ri-facebook-fill"></i>
                                </a>
                            </li>
                            <li>
                                <a href="https://twitter.com/" target="_blank">
                                    <i class="ri-twitter-line"></i>
                                </a>
                            </li>
                            <li>
                                <a href="https://linkedin.com/" target="_blank">
                                    <i class="ri-linkedin-fill"></i>
                                </a>
                            </li>
                            <li>
                                <a href="https://instagram.com/" target="_blank">
                                    <i class="ri-instagram-line"></i>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>

                <div class="col-xl-5">
                    <div class="banner-img wow fadeInUp delay-0-6s">
                        <img src="@/assets/images/banner/banner-img-1.png" class="banner-img-1" alt="Изображение" />
                        <img src="@/assets/images/banner/banner-img-shape-1.png" class="banner-shape-1" alt="Изображение" />
                        <img src="@/assets/images/banner/banner-img-shape-2.png" class="banner-shape-2" alt="Изображение" />
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="appointment-area bg-color-ffffff ptb-100">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <div class="appointment-img wow fadeInLeft delay-0-2s">
                        <img src="@/assets/images/appointment-img.png" alt="Изображение" />
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="appointment-content wow fadeInRight delay-0-2s">
                        <span class="top-title">Записаться на приём</span>
                        <h2>Свяжитесь с нами для любой медицинской помощи и заполните форму записи на приём</h2>

                        <form class="appointment-form">
                            <div class="row">
                                <div class="col-lg-6 col-sm-6">
                                    <div class="form-group">
                                        <label>Полное имя</label>
                                        <input type="text" class="form-control" placeholder="Ереке" />
                                        <i class="ri-user-line"></i>
                                    </div>
                                </div>
                                <div class="col-lg-6 col-sm-6">
                                    <div class="form-group">
                                        <label>Адрес электронной почты</label>
                                        <input type="email" class="form-control" placeholder="ereke@gmail.com" />
                                        <i class="ri-mail-line"></i>
                                    </div>
                                </div>
                                <div class="col-lg-6 col-sm-6">
                                    <div class="form-group">
                                        <label>Номер телефона</label>
                                        <input type="text" class="form-control" placeholder="+7(747) 409 2621" />
                                        <i class="ri-phone-line"></i>
                                    </div>
                                </div>
                                <div class="col-lg-6 col-sm-6">
                                    <div class="form-group">
                                        <label>Дата записи</label>
                                        <input type="date" class="form-control" placeholder="12/03/2022" />
                                    </div>
                                </div>
                                <div class="col-lg-6 col-sm-6">
                                    <div class="form-group">
                                        <label>Время</label>
                                        <select class="form-select form-control" aria-label="По умолчанию выбрано значение">
                                            <option selected>10:00 - 12: 00</option>
                                            <option value="1">12:00 - 14:00</option>
                                            <option value="2">14:00 - 16:00</option>
                                            <option value="3">16:00 - 18:00</option>
                                        </select>
                                    </div>
                                </div>
                                <div class="col-lg-6 col-sm-6">
                                    <div class="form-group">
                                        <label>Врач</label>
                                        <select class="form-select form-control" aria-label="По умолчанию выбрано значение">
                                            <option selected>Выберите врача</option>
                                            <option value="1">Ереке</option>
                                            <option value="2">Нуреке</option>
                                            <option value="3">Баке</option>
                                        </select>
                                    </div>
                                </div>
                                <div class="col-lg-12">
                                    <div class="d-flex submit-btn align-items-center">
                                        <button type="submit" class="default-btn">Подтвердить запись на приём</button>
                                        <ul>
                                            <li>
                                                <div class="form-check">
                                                    <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1" />
                                                    <label class="form-check-label" for="flexRadioDefault1"> Мужской </label>
                                                </div>
                                            </li>
                                            <li>
                                                <div class="form-check">
                                                    <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault2" />
                                                    <label class="form-check-label" for="flexRadioDefault2"> Женский </label>
                                                </div>
                                            </li>
                                            <li>
                                                <div class="form-check">
                                                    <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault3" />
                                                    <label class="form-check-label" for="flexRadioDefault3"> Не хочу раскрывать </label>
                                                </div>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="solutions-area ptb-100">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <div class="solutions-content wow fadeInLeft delay-0-2s">
                        <span class="top-title">Решения потребительского телемедицинского здравоохранения</span>
                        <h2>Телемедицинская платформа предоставляет решения для всех видов проблем</h2>
                        <div class="accordion" id="accordionExample">
                            <div class="accordion-item">
                                <h2 class="accordion-header" id="headingOne">
                                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">Улучшенный доступ к здоровью</button>
                                </h2>

                                <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                                    <div class="accordion-body">
                                        <p>Телемедицинская платформа предоставляет решения для всех видов проблем <RouterLink to="/">Свяжитесь с нами</RouterLink>.</p>
                                    </div>
                                </div>
                            </div>

                            <div class="accordion-item">
                                <h2 class="accordion-header" id="headingTwo">
                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">Управление назначениями</button>
                                </h2>
                                <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                                    <div class="accordion-body">
                                        <p>Телемедицинская платформа предоставляет решения для всех видов проблем</p>
                                    </div>
                                </div>
                            </div>

                            <div class="accordion-item">
                                <h2 class="accordion-header" id="headingThree">
                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">Управление клиническими данными</button>
                                </h2>
                                <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                                    <div class="accordion-body">
                                        <p>Телемедицинская платформа предоставляет решения для всех видов проблем</p>
                                    </div>
                                </div>
                            </div>

                            <div class="accordion-item">
                                <h2 class="accordion-header" id="headingFour">
                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFour" aria-expanded="false" aria-controls="collapseFour">Посвященное обеспечение качества</button>
                                </h2>
                                <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour" data-bs-parent="#accordionExample">
                                    <div class="accordion-body">
                                        <p>Телемедицинская платформа предоставляет решения для всех видов проблем</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="solutions-img wow fadeInRight delay-0-2s">
                        <img src="@/assets/images/solutions-img.jpg" alt="Изображение" />

                        <div class="play-button">
                            <a href="https://www.youtube.com/watch?v=PD-ucQ7EAl4" class="video-btn popup-youtube">
                                <i class="ri-play-fill"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
