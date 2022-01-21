# Abstract Factory

## Also Knonwn as

---

Kit

## 의도

---

구체적인 클래스를 지정하지 않고 관련 객체 또는 종속 객체의 패밀리를 작성할 수 있는 인터페이스를 제공하기 위함

## 설명

---

Real-world example

> To create a kingdom we need objects with a common theme. The elven kingdom needs an elven king, elven castle, and elven army whereas the orcish kingdom needs an orcish king, orcish castle, and orcish army. There is a dependency between the objects in the kingdom.

In plain words

> A factory of factories; a factory that groups the individual but related/dependent factories together without specifying their concrete classes.

Wikipedia says

> The abstract factory pattern provides a way to encapsulate a group of individual factories that have a common theme without specifying their concrete classes

## 코드 설명

---

코드를 활용해 왕국을 만들어보겠습니다.
먼저, 왕국에 필요한 요소들에 대한 interface와 implemation을 만들어보겠습니다.
