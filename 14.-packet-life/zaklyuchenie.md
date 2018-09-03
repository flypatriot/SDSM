# Заключение

Как вы уже, вероятно, поняли из безумного количества if'ов выше, описать аппаратную коммутацию на вендоронезависимом универсальном языке невозможно. Хуже того, даже если брать одного вендора, разные его линейки оборудования и даже разные платы используют совершенно разную архитектуру.  
Так, например, у Cisco есть платформы с программной маршрутизацией, а есть с аппаратной.  
Или на Huawei интерфейсная очередь может быть реализована на чипе ТМ, а может на PIC.  
Или там, где Cisco использует сетевые процессоры, Juniper обходится ASIC'ами.

Для коробочного устройства нужно убрать фабрики коммутации и поиск выходного чипа.  
В маршрутизаторах сегмента SOHO, наверняка, будут отсутствовать CAM/TCAM.  
Хореография вокруг очередей, которые могут быть сделаны тысячей различных способов, заслуживает отдельных 600 страниц в книге «Соседняя очередь движется быстрее. История потерянного RFC».

Что уж говорить о современном мире виртуализации, где свергают старых правителей и возводят на трон новых.

Почти в каждом параграфе опытный и въедливый читатель найдёт, что следует уточнить, где дать более развёрнутые объяснение. И будет прав… и не прав в то же время. У меня были долгие сомнения, ставить ли в заголовок «маленьких» или «матёрых». И я поставил «маленьких», потому что это только введение в безграничный мир аппаратной коммутации, которое не требует глубоких знаний протоколов или электротехники, а если я начну погружаться в тонкости реализаций различных вендоров, то рискую никогда уже не выбраться из стремительного водоворота деталей.

Я надеюсь, что данная статья послужит отправной точкой в вашем личном путешествии длиною в жизнь.
