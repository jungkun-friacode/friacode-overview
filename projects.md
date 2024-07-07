---
title: Projects
layout: landing
description: 프리아코드에서 진행 했던 프로젝트를 소개 합니다
image: assets/images/project.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>장애인인권센터</h2>
		</header>
		<p>프리아코드로 처음 진행한 프로젝트 입니다. Python-Django 로 개발 했으며, 장애인인권센터에 오는 문의와 히스토리를 관리하는 시스템을 개발 하였습니다. DB 설계 및 관리자 화면 개발, 비지니스 로직 개발을 포함해서 풀 스택으로 개발 진행 하였습니다. 프로젝트 개발 기간은 1개월 진행 하였으며, 1년 유지보수 계약 후 종료 되었습니다.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="projects.html" class="image">
			<img src="{% link assets/images/jn.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>J& 컴퍼니 HR 리포트 관리 시스템</h3>
				</header>
				<p>J& 컴퍼니는 기업들에 HR 솔루션을 제공하는 회사 입니다. 의뢰받은 회사의 직원들에게 설문지를 작성하게 한 후 데이터를 분석해서 리포트를 제작해 제공 합니다. 엑셀로 데이터를 관리하고 있었고 대부분의 직원들이 엑셀 데이터를 정리하는데 많은 시간을 사용하고 있어서 시스템 도입의 필요성을 느끼고 의뢰받아 프로젝트에 참여하게 되었습니다. 엑셀로 받은 직원들의 설문 데이터를 파싱해서 DB에 저장 후 직원별로 새로 디자인 된 PDF 리포트를 출력할 수 있는 시스템을 개발 하였습니다. Python-Django 기반으로 개발하였으며, DB 설계와 비지니스 로직 개발, 리포트 퍼블리싱 및 최적화 등 프로덕트 전반에 걸쳐 참여 하였습니다. 시스템 도입 후 J& 컴퍼니의 직원들이 하던 업무를 시스템으로 완전히 전환할 수 있었고, 성공적으로 프로젝트를 완료하여 해당 회사로 인수를 완료 하였습니다.</p>
			</div>
		</div>
	</section>
	<section>
		<a href="projects.html" class="image">
			<img src="{% link assets/images/maison21g.png %}" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Maison21G</h3>
				</header>
				<p>향수 쇼핑몰 Maison21G 프론트엔드 개발 프로젝트 입니다. 프로젝트 수주 회사는 벡엔드 개발자만 있어서 프리아코드에서 프론트엔드 개발을 담당하였습니다. 프로젝트가 여러번 엎어졌던 상황에서 저희가 개발할 수 있는 기간이 2개월 정도 남아 있었던 상황 이었습니다. 디자인과 퍼블리싱도 완성되지 않았던 상황이라 개발에 필요한 절대적 시간이 부족한 상황에서 시작하게 되었습니다. Vue를 사용해서 개발했으며, 백엔드와 잘 협업 하면서 쇼핑몰 오픈 시간에 맞춰서 성공적으로 오픈할 수 있었습니다. gitlab으로 프로젝트 이슈 관리와 코드 관리를 하였고 vercel 로 자동 배포 시스템을 구축해서 완료 하였습니다. 지난 1년 유지보수 계약을 해서 계속 관리를 해 왔으며, 현재도 계약 연장을 해서 유지보수 진행 중 입니다.</p>
				<ul class="actions">
					<li><a href="https://www.maison21g.co.kr/" class="button">Website</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="projects.html" class="image">
			<img src="{% link assets/images/hatchery2.png %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Hatchery(해처리 - 농산물 데이터 분석)</h3>
				</header>
				<p>해처리는 농산물 데이터를 분석해서 생산량을 예측하고 결과를 제공하는 회사 입니다. 농산물 예측, 데이터 추출과 같은 core 기술은 해처리 측에서 보유하고 있으며, 프리아코드는 분석된 데이터를 화면에 보여주고 그래프를 만드는 프론트엔드 작업을 하였습니다. React 기반의 NextJS 로 작업을 하였고, 다양한 그래프 라이브러리를 커스텀 해서 작업하였습니다. 특히, 카카오 Map api 를 사용해서 재배면적 표시와 작황이 무엇인지 등을 시각적으로 표시해 주고 데이터도 보여주는 작업을 완료 하였습니다.</p>
				<ul class="actions">
					<li><a href="https://observer.hatchery.kr/" class="button">Website</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>
</div>
