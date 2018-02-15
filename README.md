# Stuff I read, watch and listen to
_Inspired by [project](https://github.com/chtefi/every-single-day-i-tldr) of Stéphane Derosiaux_

## 15.02.18
* https://blog.softwaremill.com/dont-fear-the-main-1b9612ea6467 Let's make main method great again!

## 13.02.18
* https://anadea.info/blog/scala-implicits How compiler translates implicits.
* https://vincibean.github.io/2018/02/07/Variance-in-Scala.html Interesting examples of variance in Scala.

## 09.02.18
* https://softwaremill.com/comparing-scala-relational-database-access-libraries/ Comparison of Slick/Doobie/Quill/ScalikeJDBC

## 07.02.18
* https://medium.com/@sebastienphl/how-to-stop-forgetting-what-you-read-aa2126f722 Approach to the four levels of reading and note-taking
* https://www.scotthyoung.com/blog/2015/06/22/stop-forgetting/ Recall by questions, not by statements.
* http://blog.ezyang.com/2010/10/rapid-prototyping-in-haskell/ Meet Haskell the scripting language!
* https://mmhaskell.com/blog/2017/4/3/compile-driven-learning Write stubs for methods -> Implement one by one.

## 06.02.18
* https://www.scotthyoung.com/blog/2018/01/31/set-goals-in-the-middle/ No need to set goals at the start, one can come up with them when they become clearer.
* http://calnewport.com/blog/2018/02/02/on-simple-productivity-systems-and-complex-plans/ Simplicity over powerfulness in productivity systems.
* https://eclectic614387068.wordpress.com/2018/01/26/emacs-lisp-is-fun/ Emacs Lisp is not that difficult language.

## 04.02.18
* https://blog.ianholden.com/using-markdown-with-evernote/ First option doesn't work for me, but Marxico (markdown integration for Evernote) seems pretty cool.
* http://eed3si9n.com/removing-commas-with-sbt-nocomma Sbt settings without commas.
* https://kafka.apache.org/10/documentation/streams/ Good explanation of KTables, KStreams and Windows.
* https://www.ctheu.com/2017/08/07/looking-at-kafka-s-consumers-offsets/ From Kafka 0.9 there is no need in storing offsets using Zookeeper, there is built-in topic for this purpose.

## 03.02.18
* https://www.confluent.io/blog/introducing-kafka-streams-stream-processing-made-simple/ Kafka Streams designed to be simple, built on top of kafka itself (input and output are different topics), has a little overhead, solves "out-of-order" data problem, fully integrates the concepts of tables and streams, can be used with orchestration tools.
* https://kafka.apache.org/10/documentation/streams/quickstart Examples of execution terminal tools to play with Kafka.
* https://content.pivotal.io/blog/understanding-when-to-use-rabbitmq-or-apache-kafka RabbitMQ has better integration (languages, visualization/monitoring tools) and security, Kafka has better performance and more suitable for event sourcing model.

## 02.02.18
* https://bravenewgeek.com/you-cannot-have-exactly-once-delivery/ One can only simulate exactly-once delivery by making recovering messages idempotent.
* http://www.dwmkerr.com/the-death-of-microservice-madness-in-2018/ Pros and cons of using microservices pattern.

## 01.02.18
* https://medium.com/@otto.chrons/what-makes-scalafiddle-so-fast-9a3edf33ed4d Amazing explanation about how Scalafiddle works and why it's so fast.
* https://gorillalogic.com/blog/continuous-integration-systems-circleci-vs-travisci-vs-codeship-vs-jenkins-part-2/ Comparing popular CI tools.

## 31.01.18
* http://blog.dblazejewski.com/2018/01/aws-sqs-alpakka-akka-streams-go-reactive-part-1/ Intro to the series of posts about migration from AWS ElasticBeanstalk to AkkaStreams. Starts with explanation reactive model.
* https://docs.docker.com/compose/gettingstarted/#step-8-experiment-with-some-other-commands Simple guide for using docker-compose with your own code and images attached.

## 30.01.18
* https://www.lightbend.com/blog/introducing-akka-multi-data-center-clustering-and-persistence Extension for Akka Cluster to support effective communication for data centers distributed all over the world. New Persisting API is a commercial feature.

## 29.01.18
* https://www.cakesolutions.net/teamblogs/2011/12/19/cake-pattern-in-depth Cake pattern in practice with test example.
* https://blog.knoldus.com/2012/10/31/solid-principles-with-scala/ Examples of SOLID patterns implemented in Scala.

## 27.01.18
* https://shift.newco.co/what-its-like-to-be-a-woman-at-a-tech-conference-8a1a299ac82b Set of stories about attending tech conferences by a woman.
* https://blog.couchbase.com/optimistic-or-pessimistic-locking-which-one-should-you-pick/ Differences and use cases of optimistic and pessimistic locks.
* https://developer.lightbend.com/blog/2017-05-17-atotm-clustering-and-remoting/index.html Gentle introduction to Akka clustering.

## 25.01.18 
* https://blog.evernote.com/blog/2017/04/12/do-lists-vs-done-lists-jot-down-small-wins-amplify-success/ Done lists is a powerful instrument that helps you to stay motivated to do things.
* https://medium.com/taking-note/why-the-journey-matters-more-than-your-goal-7aad1835093a Tips for achieving your goals by simply focusing on doings rather than on results.
* https://blog.redelastic.com/diving-into-akka-streams-2770b3aeabb0 Introduction to Akka Streams with core concepts (shapes, fans, materialization) briefly explained.
* http://scalalaz.ru/series-37.html Scalalaz podcast about functional programming, linear algebra, type driven development with Idris, Kafka testing, etc. 