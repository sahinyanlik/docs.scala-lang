---
layout: tour
title: Giriş
partof: scala-tour

num: 1

next-page: basics

redirect_from: "/tutorials/tour/tour-of-scala.html"
redirect_from: "/tutorials/tour/anonymous-function-syntax.html"
redirect_from: "/tutorials/tour/explicitly-typed-self-references.html"
---

## Scala Turu
Bu tur Scala dilinde en fazla kullanılan özellikleri kısaca anlatmayı amaçlamaktadır. Bu dile yeni başlayanlar hedeflenmektedir.


Bu kısa bir eğitimdir ve tüm dili kapsamayacaktır. Eğer dildeki tüm özellikleri öğrenmek istiyorsanız. Bunun için [kitap](/books.html) veya [danışmanlık](/learn.html) edinin.

## Scala Nedir?
Scala bir çok paradigmayı genel olarak kullanılan kalıplarla şık, tip-güvenli bir şekilde program yazmanıza yarayan bir dildir. Nesne yönelimli ve fonksiyonel özellikleri içeririr.

## Scala Nesne Yönelimlidir  ##
Scala saf bir nesne-yönelimli programlama dilidir. Bundan dolayı [Her değer objedir](unified-types.html). Tipler ve bunların davranışları [sınıf](classes.html)'da belirlenir. Alt sınfılama için [traitler](traits.html) ve daha esnek yapılar ile [mixin-tabanlı birleştirme](mixin-classes-composition.html) çoklu kalıtım yerine daha temiz bir yapıya geçilmiş olur.

## Scala Fonksiyoneldirl ##
Scala ayrıca fonksiyonel bir dildir. Bundan dolayı [her fonksiyon bir değerdir](unified-types.html). Scala isimsi fonksiyon tanımlama için [hafif bir yazım](basic.html#functions)'a sahiptir, ayrıca [üst seviye fonksiyonları](higher-order-functions.html) destekler. Fonksiyonların [iç içe kullanılmasını](nested-functions.html) ve  [tımarlamayı](multiple-parameter-lists) destekler. Scala'nın [case sınıfları](case-classes.html) ve bunların [örüntü eşleme](pattern-matching.html) gibi varsayılanları çoğu fonksiyonel dilde kullanılmaktadır. [Singleton Objeler](singleton-objects.html) bir sınıfa dahil olmayan fonksiyonların gruplanmasını kolaylaştırır. 


Furthermore, Scala's notion of pattern matching naturally extends to the [processing of XML data](https://github.com/scala/scala-xml/wiki/XML-Processing) with the help of [right-ignoring sequence patterns](regular-expression-patterns.html), by way of general extension via [extractor objects](extractor-objects.html). In this context, [for comprehensions](for-comprehensions.html) are useful for formulating queries. These features make Scala ideal for developing applications like web services.

## Scala is statically typed ##
Scala's expressive type system enforces, at compile-time, that abstractions are used in a safe and coherent manner. In particular, the type system supports:

* [generic classes](generic-classes.html)
* [variance annotations](variances.html)
* [upper](upper-type-bounds.html) and [lower](lower-type-bounds.html) type bounds,
* [inner classes](inner-classes.html) and [abstract type members](abstract-type-members.html) as object members
* [compound types](compound-types.html)
* [explicitly typed self references](self-types.html)
* [implicit parameters](implicit-parameters.html) and [conversions](implicit-conversions.html)
* [polymorphic methods](polymorphic-methods.html)

[Type inference](type-inference.html) means the user is not required to annotate code with redundant type information. In combination, these features provide a powerful basis for the safe reuse of programming abstractions and for the type-safe extension of software.

## Scala is extensible ##

In practice, the development of domain-specific applications often requires domain-specific language extensions. Scala provides a unique combination of language mechanisms that make it easy to smoothly add new language constructs in the form of libraries.

In many cases, this can be done without using meta-programming facilities such as macros. For example,

* [Implicit classes](/overviews/core/implicit-classes.html) allow adding extension methods to existing types.
* [String interpolation](/overviews/core/string-interpolation.html) is user-extensible with custom interpolators.

## Scala interoperates

Scala is designed to interoperate well with the popular Java Runtime Environment (JRE). In particular, the interaction with the mainstream object-oriented Java programming language is as smooth as possible. Newer Java features like SAMs, [lambdas](higher-order-functions.html), [annotations](annotations.html), and [generics](generic-classes.html) have direct analogues in Scala.

Those Scala features without Java analogues, such as [default](default-parameter-values.html) and [named parameters](named-arguments.html), compile as close to Java as they can reasonably come. Scala has the same compilation model (separate compilation, dynamic class loading) like Java and allows access to thousands of existing high-quality libraries.

## Enjoy the tour!

Please continue to the [next page](basics.html) in the Contents menu to read more.
