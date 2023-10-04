# Awesome CAPTCHA - biblioteki CAPTCHA i narzędzia do ich łamania [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Wyselekcjonowana lista wspaniałych bibliotek CAPTCHA i narzędzi do łamania CAPTCHA.
> CAPTCHA (Completely Automated Public Turing test to tell Computers and Humans Apart)

[CAPTCHA](https://pl.wikipedia.org/wiki/CAPTCHA) to rodzaj techniki stosowanej jako zabezpieczenie na stronach internetowych, celem której jest dopuszczenie do przesłania danych tylko wypełnionych przez człowieka.


[English](README.md) | [中文](README-zh.md) | [Polish](README-pl.md)

## Zawartość

- [Biblioteki](#biblioteki)
- [Generowanie](#generowanie)
- [Łamanie](#łamanie)
  - [Ogólne](#ogólne)
  - [Chińskie](#chińskie)
- [Narzędzia](#narzędzia)
- [Inne](#inne)
- [Opiekunowie](#opiekunowie)
- [Współtworzenie](#współtworzenie)


## Biblioteki

- [mewebstudio/captcha](https://github.com/mewebstudio/captcha) - CAPTCHA dla Laravel 5.
- [CGregwar/Captcha](https://github.com/Gregwar/Captcha) - Biblioteka PHP CAPTCHA.
- [trekjs/captcha](https://github.com/trekjs/captcha) - A Lightweight Pure JavaScript CAPTCHA dla Node.js. No C/C++, No ImageMagick, No Canvas.
- [patchca](https://code.google.com/archive/p/patchca) - Prosta, ale potężna biblioteka CAPTCHA napisana w Javie.
- [google/recaptcha](https://github.com/google/recaptcha) - Biblioteka klienta PHP dla reCAPTCHA, bezpłatna usługa chroniąca twoją stronę przed spamem i nadużyciami.
- [ambethia/recaptcha](https://github.com/ambethia/recaptcha) - ReCaptcha helpers dla aplikacji Ruby.
- [anhskohbo/no-captcha](https://github.com/anhskohbo/no-captcha) - No CAPTCHA reCAPTCHA dla Laravel.
- [lorien/captcha_solver](https://github.com/lorien/captcha_solver) - Universal python API do różnych usług rozwiązywania CAPTCHA.


## Generowanie
- [dchest/captcha](https://github.com/dchest/captcha) - pakiet Go CAPTCHA implementuje generowanie i weryfikację obrazu i dźwięku CAPTCHA.
- [lepture/captcha](https://github.com/lepture/captcha) - biblioteka CAPTCHA która generuje CAPTCHA audio oraz obraz.
- [lemonce/svg-captcha](https://github.com/lemonce/svg-captcha) - generuje svg CAPTCHA w Node.js.
- [DoubleSpout/ccap](https://github.com/DoubleSpout/ccap) - Node.js generuje CAPTCHA używając biblioteki C++ CImg bez instalacji żadnych innych bibliotek lub oprogramowania.
- [contra/captchagen](https://github.com/contra/captchagen) - generowanie CAPTCHA dla Node.js.
- [jineshfrancs/CaptchaImageView](https://github.com/jineshfrancs/CaptchaImageView) - Custom ImageView dla generowania obrazu CAPTCHA.
- [mcxtzhang/SwipeCaptcha](https://github.com/mcxtzhang/SwipeCaptcha) - Swipe CAPTCHA platformy Android.
- [mojocn/base64Captcha](https://github.com/mojocn/base64Captcha) - Golang base64-captcha obsługujące cyfry, liczby, alfabet, arytmetykę, audio i cyfry-alfabet CAPTCHA.

## Łamanie

### Ogólne
- [arunpatala/captcha](https://github.com/arunpatala/captcha) - łamanie CAPTCHA używając torch.
- [zakizhou/CAPTCHA](https://github.com/zakizhou/CAPTCHA) - implementacja klasyfikacji dla CAPTCHA w TensorFlow.
- [nladuo/captcha-break](https://github.com/nladuo/captcha-break) - łamanie CAPTCHA oparte na opencv2, tesseract-ocr i algorytmie uczenia maszynowego.
- [ypwhs/captcha_break](https://github.com/ypwhs/captcha_break) - łamanie CAPTCHA używając CNN z Keras.
- [ptigas/simple-captcha-solver](https://github.com/ptigas/simple-captcha-solver) - Simple CAPTCHA Solver w Python 🐍.
- [rickyhan/SimGAN-Captcha](https://github.com/rickyhan/SimGAN-Captcha) - rozwiązywanie CAPTCHA bez ręcznego oznaczania zestawu treningowego.
- [arunpatala/captcha.irctc](https://github.com/arunpatala/captcha.irctc) - czytanie irctc CAPTCHAs z 98% dokładnością za pomocą deep learning.
- [JackonYang/captcha-tensorflow](https://github.com/JackonYang/captcha-tensorflow) - Image CAPTCHA Solving używając TensorFlow oraz CNN Model.
- [skyduy/CNN_keras](https://github.com/skyduy/CNN_keras) - CNN | Keras | CAPTCHA recognition（卷积神经网络、Keras框架、验证码识别）.
- [PatrickLib/captcha_recognize](https://github.com/PatrickLib/captcha_recognize) - Image Recognition CAPTCHA bez segmentacji obrazu.
- [zhengwh/captcha-svm](https://github.com/zhengwh/captcha-svm) - Use svm to hack simple CAPTCHA.
- [chxj1992/captcha_cracker](https://github.com/chxj1992/captcha_cracker) - Łamanie CAPTCHA z CNN.
- [chxj1992/slide_captcha_cracker](https://github.com/chxj1992/slide_captcha_cracker) - rozwiązanie łamania dla slide CAPTCHA z algorytmem Canny.
- [JasonLiTW/simple-railway-captcha-solver#english-version](https://github.com/JasonLiTW/simple-railway-captcha-solver#english-version) - Simple CAPTCHA solver oparty na CNN oraz generator zestawu treningowego poprzez naśladowanie stylu CAPTCHA.
- [lllcho/CAPTCHA-breaking](https://github.com/lllcho/CAPTCHA-breaking) - Breaking the CAPTCHA.
- [ecthros/uncaptcha](https://github.com/ecthros/uncaptcha) - Pokonanie reCAPTCHA Google'a z 85% dokładnością.
- [dessant/buster](https://github.com/dessant/buster) - CAPTCHA solver extension for humans and monsters.
- [kerlomz/captcha_trainer](https://github.com/kerlomz/captcha_trainer) - oparte na CNN5/DenseNet+BLSTM/LSTM+CTC do realizacji identyfikacji kodu weryfikacyjnego. Tylko do treningu modelu.

### Chińskie
- [burness/chinese_hand_write_rec](https://github.com/burness/tensorflow-101/tree/master/chinese_hand_write_rec/src) - rozpoznawanie chińskiego pisma ręcznego.
- [taosir/cnn_handwritten_chinese_recognition](https://github.com/taosir/cnn_handwritten_chinese_recognition) - tak jak wskazuje nazwa, handwritten_chinese_recognition z cnn.
- [soloice/Chinese-Character-Recognition](https://github.com/soloice/Chinese-Character-Recognition) - ten projekt pokazuje jak używać CNN, aby wykonać rozpoznawanie chińskich znaków, jest to znacznie bardziej skomplikowane zadanie w porównaniu do rozpoznawania cyfr MNIST.
- [muchrooms/zheye](https://github.com/muchrooms/zheye) - Chinese CAPTCHA recognition program for handstand character of zhihu.
- [aaronshan/12306-captcha](https://github.com/aaronshan/12306-captcha) - Recognize 12306 captcha with deep learning.
- [nickliqian/cnn_captcha](https://github.com/nickliqian/cnn_captcha) - Use cnn recognize CAPTCHA by Tensorflow.


## Narzędzia

- [Tesseract](https://github.com/tesseract-ocr/tesseract) - Tesseract Open Source OCR Engine (silnik optycznego rozpoznawania znaków).
- [MotionCAPTCHA](https://github.com/wjcrowcroft/MotionCAPTCHA) - MotionCAPTCHA jQuery Plugin - Stop Spam, Draw Shapes.
- [Negative-captcha](https://github.com/subwindow/negative-captcha) - Wtyczka sprawiająca, że proces tworzenia negative CAPTCHA w Railsach jest o wiele mniej bolesny.
- [Django-simple-captcha](https://github.com/mbi/django-simple-captcha) - Niezwykle prosta, ale wysoce konfigurowalna aplikacja Django do dodawania obrazów CAPTCHA do dowolnej formy Django.
- [Securimage](https://github.com/dapphp/securimage) - PHP CAPTCHA Script.
- [Captcha_solver](https://github.com/lorien/captcha_solver) - Univeral API do usług rozwiązywania CAPTCHA.


## Inne

- [VisualCaptcha](https://github.com/emotionLoop/visualCaptcha) - Zbiór wszystkich innych wersji/repozytoriów visualCaptcha.


## Opiekunowie

- [@ZYSzys](https://github.com/ZYSzys)


## Współtworzenie

Dołącz śmiało! Sprawdź plik [contributing.md](contributing.md) lub [otwórz issue](https://github.com/ZYSzys/awesome-captcha/issues/new)!


## Licencja

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

W zakresie, w jakim jest to możliwe na mocy prawa, [ZYSzys](https://github.com/ZYSzys) zrzekł się wszelkich praw autorskich i powiązanych lub pokrewnych do tego dzieła.

Wersja polska od: @[mbiesiad](https://github.com/mbiesiad)
