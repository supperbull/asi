# Projekty, 2016/17

Projekt na zaliczenie musi zawierać następujące elementy:

1. Co najmniej jeden model. W bazie należy zapisać sporo **sensownych** danych wpisanych w pliku _seed.rb_
  (np. można skorzystać z gemu Faker).
1. Aplikacja powinna korzystać z niestandardowych gemów, np. z jednego
  z gemów opisanych na stronie [8 Useful Ruby on Rails Gems We Couldn't Live Without](http://blog.planetargon.com/entries/8-useful-ruby-on-rails-gems-we-couldnt-live-without?__s=jvsvsq3unktoidfpqwzm).
  Gemy _device_, _will_paginate_ to gemy standardowe.
1. Widoki i layout aplikacji w jednym z frameworków:
   Bootstrap, Foundation, Materialize lub innym (musi być responsywny).
1. Autoryzacja (logowanie) – [ActionController::HttpAuthentication::Basic](http://edgeapi.rubyonrails.org/classes/ActionController/HttpAuthentication/Basic.html)
   lub z książki [https://www.railstutorial.org/book](https://www.railstutorial.org/book)
   (rozdziały 6-10) lub OAuth2 + GitHub.
1. Czasami konkretny gem może nie działać z ostatnią wersją Rails. Można wtedy spróbować
  wersję z gałęzi master z repozytorium z kodem. Na przykład tak instalujemy
  gem Devise wpisując go w pliku _Gemfile_ w taki sposób
  ([zob. też](http://bundler.io/git.html)):

```ruby
gem 'devise', :github => 'plataformatec/devise'
```
Można tez zainstalować (i użyć) wersji _prerelease_:
```sh
gem install carrierwave --pre # jest już wersja 1.0.0
gem install cloudinary # swoje obrazki http://cloudinary.com/
```

## Projekty indywidualne (zaliczenie)

Pull request według schematu:
```
1. [Nazwisko, Imię](link do repo z kodem applikacji). [Nazwa aplikacji](link do wdrożonej aplikacji)
```

Dodatkowe informacje na temat _pull requests_: Scott Chacon and Ben Straub,
[Contributing to a Project on the GitHub](https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project)
(rozdział 6 książki [Pro Git](https://git-scm.com/book/en/v2))
Michael Hartl, [Learn Enough Git to Be Dangerous](https://www.learnenough.com/git-tutorial).

<!--
  Regular Expressions Tutorial, http://www.regular-expressions.info/tutorial.html
     Find: (\d+),(.+),(.+),.+,.*
  Replace: $1. $2, $3
-->

## Laboratorium (prezentacje projektów)

W związku z awarią sufitu, decyzją inspektora technicznego, 
laboratorium 25 zostało zamknięte do odwołania. Dlatego
zmieniłem godziny i salę. 

**NEW!** p. 121, grupa 1. – 10:45, 2. – 12:15, 3. – 15:15.


## Projekty zespołowe (egzamin = średnia z zaliczenia i projektu)

<!--
W pliku _README.md_ z repozytorium należy wpisać wszystkich autorów aplikacji
i następnie wykonać pull request, który dopisze linijkę tekstu do tego pliku
utworzoną według poniższego schematu:

```
1. [Nazwa zespołu](link do repo z kodem). [Nazwa aplikacji](link do wdrożonej aplikacji) (gdzie wdrożono)
```
-->

1. [Patryk Adler & Radosław Gołuński & Tomek Cabaj](https://github.com/adlerpoland/mojeasi). [Photo Gallery](https://protected-ocean-44249.herokuapp.com/photos) (Heroku, Cloudinary)
1. [Ciamciaramcia](https://github.com/atejszerska/ruby-asi-zespolowy). [Tramwaje Gdańsk](https://tramwaje-gdansk.herokuapp.com) (Heroku)
1. [Dawid Cwilik & Martyna Pyszyńska & Daria Wieliczko](https://github.com/Ruby-team/NotesExamProject). [NoteManager](https://note-manager.herokuapp.com/)
1. [Mateusz Gawin](https://github.com/matgawin/projekt_asi2). [Blog](https://asi-blog.herokuapp.com/) (Heroku)
1. [Jakub Jabłoński](https://github.com/jakjablonski/ASI-my). [Blog](https://rocky-beach-30006.herokuapp.com/) (Heroku)
1. [GL&HF](https://github.com/mkassjanski/asi-egzamin). [Flicks 2.0](https://flicks2.herokuapp.com/) (Heroku, AWS)
1. [Kaczmarz Tomasz](https://github.com/tkaczmarz/asi). [Salon samochodowy](https://shielded-tundra-94334.herokuapp.com)
1. [Damian Kalinowski, Rafał Lewandowski](https://github.com/lafreak/penny-auctions). [Penny Auctions](https://penny-auctions.herokuapp.com) (Heroku, Cloudinary)
1. [Kamil Kot](https://github.com/KotMeow/asi-frameworks). [Frameworks](https://asi-frameworks.herokuapp.com/) (Heroku)
1. [Daria Kotowicz](https://github.com/dkotowicz/ruby_projekt2.git). [Blog]
1. [Piotr Laskowski, Jakub Wiśniewski](https://github.com/ozh204/ruby-egz). [Gofry](https://ozh204-gofry.herokuapp.com/) (Heroku, DropBox)
1. [Lis, Marcin](https://github.com/marcinlis0/MoviesRating). [MoviesRating](http://rate-this.herokuapp.com/)
1. [Rafał Lisiecki](https://github.com/littlefoxmiastko/ruby1). [Księga wydatków samochodowych](http://ec2-34-208-194-252.us-west-2.compute.amazonaws.com/) (AWS)
1. [Paweł Luszuk, Adam Makiewicz, Jakub Łąkowski](https://github.com/kubalakowski/daily-challenge). [Daily challenge](https://daily-code-challenge.herokuapp.com/) (Heroku)
1. [Wojciech Łojkowski i Kacper Narożnik](https://github.com/wlojkowski/AlbumWebApp). [AlbumWeb App](https://albumwebapp.herokuapp.com/) (Heroku)
1. [Sebastian Majewski](https://github.com/SebastianMajewski/RoR-Notepad). [ROR Notepad](https://rornotepad.herokuapp.com/) (Heroku)
1. [OJA](https://github.com/lic-planer/ruby_zespolowy). [Filmy animowane](https://shrouded-ocean-49748.herokuapp.com/) (Heroku)
1. [Patryk Pobłocki](https://github.com/ppoblocki/egzaminRails). [PinTab!](https://fast-shore-79390.herokuapp.com/) (Heroku, AWS)
1. [Dawid Rombel](https://github.com/drombel/project-ruby). [Lista herbart upgraded](https://lista-herbat.herokuapp.com/) (Heroku)
1. [Jacek Sasin & Łukasz Motławski](https://github.com/jsasin/asi_egzamin). [Broń](https://asiegzaminn.herokuapp.com) (Heroku)
1. [Aleksander Stefański](https://github.com/astefanski1/WhatGames). [WhatGames](https://whatgames.herokuapp.com/games) (Heroku)
1. [Wadowice Disco Fever](https://github.com/implssv/MessageApp) - [MessageApp](http://serene-spire-89656.herokuapp.com/) (Heroku)
1. [Julianna Mikucka](https://github.com/LadyJuleczka/Rails-Egzamin). [Monsters&Dragons](https://aqueous-woodland-84605.herokuapp.com/) (Heroku)
1. [Żołądek, Damian](https://github.com/damian024/rails). [Flats Catalog](https://flatcatalog.herokuapp.com/)
1. [Piotr Kawa i Szymon Świstun](https://github.com/Pkawa/Twitter-rails). [OurOwnTwitter](https://ourowntwitter.herokuapp.com/)
1. [Kamil Gniazdowski i Mikołaj Piecuch](https://github.com/mikolajpiecuch/BlaBlaRails)
1. [Mateusz Knitter](https://github.com/supperbull/antywirpak)
