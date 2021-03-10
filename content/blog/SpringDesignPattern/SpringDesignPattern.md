	AOP용어
		Aspect(Advisor) : 1. 공통 관심사 /2. Advice + Pointcuts
		Advice : 공통 관심사를 모듈화한 객체
		Join points : 공통 관심사를 적용할 수 있는 모든 대상
					Spring에서는 bean으로 등록된 모든 객체의 메서드
		Pointcuts : Join points 중 실제로 Advice가 적용 될 대상
		target : Pointcuts를 가진 객체
		Weaving : Advice와 target을 결합해 프록시 객체를 생성하는 과정
		Proxy : Addvice와 target이 결합되어 만들어진 프록시 객체

---
title: Spring design pattern
date: "2021-03-10"
description: "Spring design pattern"
---
하........

##### AOP용어 정리
- Aspect(Advisor) : 1. 공통 관심사 /2. Advice + Pointcuts
- Join points : 공통 관심사를 적용할 수 있는 모든 대상. Spring에서는 bean으로 등록된 모든 객체의 메서드
- Pointcuts : Join points 중 실제로 Advice가 적용 될 대상
- target : Pointcuts를 가진 객체
- Weaving : Advice와 target을 결합해 프록시 객체를 생성하는 과정
- Proxy : Addvice와 target이 결합되어 만들어진 프록시 객체



