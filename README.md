Lucy-XSS : Java 기반의 XSS 공격 방어 라이브러리
==================================

Lucy-XSS(Cross Site Scripting)는 악의적인 XSS 코드의 위험으로부터 웹 애플리케이션을 보호하는 아래와 같이 두 가지 방식의 방어 라이브러리를 제공한다.

	* XssFilter
		화이트리스트(White List) 설정 방식으로 구현한 Java 기반의 필터 라이브러리이다. 
		Lucy-XSS를 사용하여 전사 표준 XSS 관련 보안 정책을 적용할 수 있으며, 블랙리스트 방식을 사용하는 기존 필터보다 안전하게 웹 서비스를 제공할 수 있다.

		아래 그림은 XssFilter의 작동 구조를 나타낸 것이다. 필터링 대상 HTML 문자열이 유입되면 악의적인 XSS 코드를 제거한 후 안전한 HTML 문자열을 반환하는 구조이다.
		
		![XSSFILTER L](docs/XssFilter_Structure.png "XssFilter")
		
	* XssPreventer

화이트리스트(White List) 설정 방식으로 구현한 Java 기반의 필터 라이브러리이다. 
Lucy-XSS를 사용하여 전사 표준 XSS 관련 보안 정책을 적용할 수 있으며, 블랙리스트 방식을 사용하는 기존 필터보다 안전하게 웹 서비스를 제공할 수 있다.


Getting started
===============


Usage examples
==============


Contributing to Lucy
======================


Licensing
=========
Lucy is licensed under the Apache License, Version 2.0. See LICENSE for full license text.
