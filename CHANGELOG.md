# Changelog

## 2.0.0-a1

* Test release

## 2.0.0-b01

* Test release

## 2.0.0

* Release 2.0.0

## 2.1.0

* Update Azure Service Bus dependency to 3.4.0

## 2.2.0

* Allow `/` in queue and topic names

## 3.0.0

* Update to Rebus 3

## 4.0.0

* Update to Rebus 4
* Update to new project structure (.NET Core unfortunately not support by the driver at this time)

## 4.0.1

* Add .NET Standard 2.0 target specifically to handle dependency on `ConfigurationManager`
* `.ConfigureAwait(false)` everywhere something is `await`ed - thanks [lezzi]


[lezzi]: https://github.com/lezzi
[Meyce]: https://github.com/Meyce