<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="공업고등학교 마이크로컨트롤러 제어 프로젝트 수업 - 아두이노, 라즈베리파이, ESP32를 활용한 실습 중심 교육">
    <title>마이크로컨트롤러 제어 프로젝트 | 공업고등학교</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700;900&family=Orbitron:wght@400;700;900&display=swap"
        rel="stylesheet">
</head>

<body>
    <!-- Navigation -->
    <nav class="navbar" id="navbar">
        <div class="nav-container">
            <div class="nav-logo">
                <span class="logo-icon">⚡</span>
                <span class="logo-text">마이크로컨트롤러 제어</span>
            </div>
            <ul class="nav-menu" id="nav-menu">
                <li><a href="#home" class="nav-link">홈</a></li>
                <li><a href="#about" class="nav-link">수업소개</a></li>
                <li><a href="#curriculum" class="nav-link">커리큘럼</a></li>
                <li><a href="#projects" class="nav-link">프로젝트</a></li>
                <li><a href="#resources" class="nav-link">학습자료</a></li>
                <li><a href="#schedule" class="nav-link">수업일정</a></li>
            </ul>
            <div class="nav-toggle" id="nav-toggle">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-background">
            <div class="circuit-animation"></div>
        </div>
        <div class="hero-content">
            <h1 class="hero-title">
                <span class="title-line">마이크로컨트롤러</span>
                <span class="title-line gradient-text">제어 프로젝트</span>
            </h1>
            <p class="hero-subtitle">아두이노, 라즈베리파이, ESP32로 만드는 스마트 세상</p>
            <div class="hero-stats">
                <div class="stat-item">
                    <div class="stat-number">16</div>
                    <div class="stat-label">주차 과정</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">12</div>
                    <div class="stat-label">실습 프로젝트</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">100%</div>
                    <div class="stat-label">실습 중심</div>
                </div>
            </div>
            <a href="#curriculum" class="cta-button">
                <span>커리큘럼 보기</span>
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none">
                    <path d="M7 4L13 10L7 16" stroke="currentColor" stroke-width="2" stroke-linecap="round" />
                </svg>
            </a>
        </div>
        <div class="scroll-indicator">
            <div class="mouse">
                <div class="wheel"></div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="section" id="about">
        <div class="container">
            <h2 class="section-title">수업 소개</h2>
            <p class="section-subtitle">실무 중심의 마이크로컨트롤러 제어 기술을 배웁니다</p>

            <div class="about-grid">
                <div class="about-card" data-aos="fade-up">
                    <div class="card-icon">🎯</div>
                    <h3>수업 목표</h3>
                    <p>마이크로컨트롤러의 기본 원리를 이해하고, 센서와 액추에이터를 활용한 실제 제어 시스템을 설계하고 구현할 수 있는 능력을 배양합니다.</p>
                </div>
                <div class="about-card" data-aos="fade-up" data-aos-delay="100">
                    <div class="card-icon">💡</div>
                    <h3>학습 방법</h3>
                    <p>이론 30%, 실습 70%의 비율로 진행되며, 매 주차마다 실습 프로젝트를 통해 배운 내용을 즉시 적용하고 체득합니다.</p>
                </div>
                <div class="about-card" data-aos="fade-up" data-aos-delay="200">
                    <div class="card-icon">🚀</div>
                    <h3>진로 연계</h3>
                    <p>IoT 개발자, 임베디드 시스템 엔지니어, 스마트팩토리 전문가 등 4차 산업혁명 시대의 핵심 인재로 성장할 수 있습니다.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Curriculum Section -->
    <section class="section section-dark" id="curriculum">
        <div class="container">
            <h2 class="section-title">커리큘럼</h2>
            <p class="section-subtitle">16주간의 체계적인 학습 과정</p>

            <div class="curriculum-tabs">
                <button class="tab-button active" data-tab="beginner">초급 (1-6주)</button>
                <button class="tab-button" data-tab="intermediate">중급 (7-12주)</button>
                <button class="tab-button" data-tab="advanced">고급 (13-16주)</button>
            </div>

            <div class="curriculum-content">
                <div class="tab-content active" id="beginner">
                    <div class="week-item">
                        <div class="week-number">Week 1</div>
                        <div class="week-details">
                            <h4>마이크로컨트롤러 기초</h4>
                            <p>아두이노 개발환경 설정, 기본 구조 이해, LED 제어</p>
                            <div class="week-tags">
                                <span class="tag">아두이노</span>
                                <span class="tag">IDE</span>
                                <span class="tag">디지털 출력</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 2</div>
                        <div class="week-details">
                            <h4>디지털 입출력</h4>
                            <p>버튼, 스위치 입력 처리, 디바운싱, 7-세그먼트 제어</p>
                            <div class="week-tags">
                                <span class="tag">디지털 입력</span>
                                <span class="tag">풀업/풀다운</span>
                                <span class="tag">디스플레이</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 3</div>
                        <div class="week-details">
                            <h4>아날로그 입출력</h4>
                            <p>ADC 원리, 가변저항 읽기, PWM을 이용한 LED 밝기 조절</p>
                            <div class="week-tags">
                                <span class="tag">ADC</span>
                                <span class="tag">PWM</span>
                                <span class="tag">아날로그</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 4</div>
                        <div class="week-details">
                            <h4>센서 활용 I</h4>
                            <p>온습도 센서(DHT11), 초음파 센서(HC-SR04), 조도 센서</p>
                            <div class="week-tags">
                                <span class="tag">센서</span>
                                <span class="tag">데이터 수집</span>
                                <span class="tag">시리얼 통신</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 5</div>
                        <div class="week-details">
                            <h4>모터 제어</h4>
                            <p>DC 모터, 서보 모터, 스테핑 모터 제어 기초</p>
                            <div class="week-tags">
                                <span class="tag">모터</span>
                                <span class="tag">드라이버</span>
                                <span class="tag">액추에이터</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 6</div>
                        <div class="week-details">
                            <h4>LCD 디스플레이</h4>
                            <p>LCD 1602/2004 제어, I2C 통신, 센서 데이터 표시</p>
                            <div class="week-tags">
                                <span class="tag">LCD</span>
                                <span class="tag">I2C</span>
                                <span class="tag">디스플레이</span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="tab-content" id="intermediate">
                    <div class="week-item">
                        <div class="week-number">Week 7</div>
                        <div class="week-details">
                            <h4>시리얼 통신</h4>
                            <p>UART, SPI, I2C 통신 프로토콜 이해 및 실습</p>
                            <div class="week-tags">
                                <span class="tag">UART</span>
                                <span class="tag">SPI</span>
                                <span class="tag">I2C</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 8</div>
                        <div class="week-details">
                            <h4>블루투스 통신</h4>
                            <p>HC-06 모듈, 스마트폰 앱 연동, 무선 제어</p>
                            <div class="week-tags">
                                <span class="tag">블루투스</span>
                                <span class="tag">무선통신</span>
                                <span class="tag">앱 연동</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 9</div>
                        <div class="week-details">
                            <h4>WiFi 통신 (ESP32)</h4>
                            <p>ESP32 개발환경, WiFi 연결, 웹서버 구축</p>
                            <div class="week-tags">
                                <span class="tag">ESP32</span>
                                <span class="tag">WiFi</span>
                                <span class="tag">웹서버</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 10</div>
                        <div class="week-details">
                            <h4>IoT 플랫폼 연동</h4>
                            <p>ThingSpeak, Blynk 활용, 클라우드 데이터 저장</p>
                            <div class="week-tags">
                                <span class="tag">IoT</span>
                                <span class="tag">클라우드</span>
                                <span class="tag">데이터 분석</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 11</div>
                        <div class="week-details">
                            <h4>센서 활용 II</h4>
                            <p>가속도/자이로 센서, GPS 모듈, 기압 센서</p>
                            <div class="week-tags">
                                <span class="tag">IMU</span>
                                <span class="tag">GPS</span>
                                <span class="tag">고급센서</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 12</div>
                        <div class="week-details">
                            <h4>OLED 디스플레이</h4>
                            <p>OLED 128x64 제어, 그래픽 라이브러리, 애니메이션</p>
                            <div class="week-tags">
                                <span class="tag">OLED</span>
                                <span class="tag">그래픽</span>
                                <span class="tag">UI</span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="tab-content" id="advanced">
                    <div class="week-item">
                        <div class="week-number">Week 13</div>
                        <div class="week-details">
                            <h4>라즈베리파이 기초</h4>
                            <p>리눅스 기초, Python GPIO 제어, 카메라 모듈</p>
                            <div class="week-tags">
                                <span class="tag">라즈베리파이</span>
                                <span class="tag">Python</span>
                                <span class="tag">리눅스</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 14</div>
                        <div class="week-details">
                            <h4>영상 처리 기초</h4>
                            <p>OpenCV 기초, 객체 인식, 색상 추적</p>
                            <div class="week-tags">
                                <span class="tag">OpenCV</span>
                                <span class="tag">영상처리</span>
                                <span class="tag">AI</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 15</div>
                        <div class="week-details">
                            <h4>종합 프로젝트 설계</h4>
                            <p>팀 프로젝트 기획, 요구사항 분석, 시스템 설계</p>
                            <div class="week-tags">
                                <span class="tag">프로젝트</span>
                                <span class="tag">설계</span>
                                <span class="tag">팀워크</span>
                            </div>
                        </div>
                    </div>
                    <div class="week-item">
                        <div class="week-number">Week 16</div>
                        <div class="week-details">
                            <h4>종합 프로젝트 발표</h4>
                            <p>프로젝트 완성, 시연, 발표 및 평가</p>
                            <div class="week-tags">
                                <span class="tag">발표</span>
                                <span class="tag">시연</span>
                                <span class="tag">평가</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="section" id="projects">
        <div class="container">
            <h2 class="section-title">실습 프로젝트</h2>
            <p class="section-subtitle">실제로 만들어보는 12가지 프로젝트</p>

            <div class="projects-grid">
                <div class="project-card" data-difficulty="초급">
                    <div class="project-image" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);">
                        <div class="project-icon">💡</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty beginner">초급</span>
                        <h3>스마트 LED 조명</h3>
                        <p>버튼과 가변저항을 이용한 LED 밝기 및 패턴 제어</p>
                        <ul class="project-tech">
                            <li>디지털/아날로그 I/O</li>
                            <li>PWM 제어</li>
                        </ul>
                    </div>
                </div>

                <div class="project-card" data-difficulty="초급">
                    <div class="project-image" style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);">
                        <div class="project-icon">🌡️</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty beginner">초급</span>
                        <h3>온습도 모니터링</h3>
                        <p>DHT11 센서와 LCD를 이용한 실시간 환경 모니터</p>
                        <ul class="project-tech">
                            <li>센서 데이터 수집</li>
                            <li>LCD 디스플레이</li>
                        </ul>
                    </div>
                </div>

                <div class="project-card" data-difficulty="초급">
                    <div class="project-image" style="background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);">
                        <div class="project-icon">📏</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty beginner">초급</span>
                        <h3>초음파 거리측정기</h3>
                        <p>HC-SR04를 이용한 거리 측정 및 경고 시스템</p>
                        <ul class="project-tech">
                            <li>초음파 센서</li>
                            <li>부저 제어</li>
                        </ul>
                    </div>
                </div>

                <div class="project-card" data-difficulty="초급">
                    <div class="project-image" style="background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);">
                        <div class="project-icon">🚗</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty beginner">초급</span>
                        <h3>RC카 제어</h3>
                        <p>DC 모터와 서보 모터를 이용한 원격 조종 자동차</p>
                        <ul class="project-tech">
                            <li>모터 드라이버</li>
                            <li>무선 제어</li>
                        </ul>
                    </div>
                </div>

                <div class="project-card" data-difficulty="중급">
                    <div class="project-image" style="background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);">
                        <div class="project-icon">📱</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty intermediate">중급</span>
                        <h3>블루투스 홈 오토메이션</h3>
                        <p>스마트폰 앱으로 가전제품 제어하기</p>
                        <ul class="project-tech">
                            <li>블루투스 통신</li>
                            <li>릴레이 제어</li>
                        </ul>
                    </div>
                </div>

                <div class="project-card" data-difficulty="중급">
                    <div class="project-image" style="background: linear-gradient(135deg, #30cfd0 0%, #330867 100%);">
                        <div class="project-icon">🌐</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty intermediate">중급</span>
                        <h3>IoT 날씨 스테이션</h3>
                        <p>ESP32로 날씨 데이터를 클라우드에 전송</p>
                        <ul class="project-tech">
                            <li>WiFi 통신</li>
                            <li>클라우드 연동</li>
                        </ul>
                    </div>
                </div>

                <div class="project-card" data-difficulty="중급">
                    <div class="project-image" style="background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%);">
                        <div class="project-icon">🔐</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty intermediate">중급</span>
                        <h3>RFID 출입 시스템</h3>
                        <p>RFID 카드를 이용한 스마트 도어락</p>
                        <ul class="project-tech">
                            <li>RFID 모듈</li>
                            <li>서보 모터</li>
                        </ul>
                    </div>
                </div>

                <div class="project-card" data-difficulty="중급">
                    <div class="project-image" style="background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%);">
                        <div class="project-icon">🎮</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty intermediate">중급</span>
                        <h3>OLED 미니 게임</h3>
                        <p>OLED 디스플레이로 만드는 인터랙티브 게임</p>
                        <ul class="project-tech">
                            <li>OLED 그래픽</li>
                            <li>게임 로직</li>
                        </ul>
                    </div>
                </div>

                <div class="project-card" data-difficulty="고급">
                    <div class="project-image" style="background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);">
                        <div class="project-icon">🤖</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty advanced">고급</span>
                        <h3>라인 트레이서 로봇</h3>
                        <p>적외선 센서를 이용한 자율주행 로봇</p>
                        <ul class="project-tech">
                            <li>센서 배열</li>
                            <li>PID 제어</li>
                        </ul>
                    </div>
                </div>

                <div class="project-card" data-difficulty="고급">
                    <div class="project-image" style="background: linear-gradient(135deg, #ff6e7f 0%, #bfe9ff 100%);">
                        <div class="project-icon">📸</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty advanced">고급</span>
                        <h3>스마트 보안 카메라</h3>
                        <p>라즈베리파이로 만드는 모션 감지 카메라</p>
                        <ul class="project-tech">
                            <li>영상 처리</li>
                            <li>모션 감지</li>
                        </ul>
                    </div>
                </div>

                <div class="project-card" data-difficulty="고급">
                    <div class="project-image" style="background: linear-gradient(135deg, #e0c3fc 0%, #8ec5fc 100%);">
                        <div class="project-icon">🌱</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty advanced">고급</span>
                        <h3>스마트 팜 시스템</h3>
                        <p>자동 급수, 조명, 환경 제어 통합 시스템</p>
                        <ul class="project-tech">
                            <li>다중 센서</li>
                            <li>자동화 제어</li>
                        </ul>
                    </div>
                </div>

                <div class="project-card" data-difficulty="고급">
                    <div class="project-image" style="background: linear-gradient(135deg, #fbc2eb 0%, #a6c1ee 100%);">
                        <div class="project-icon">🎵</div>
                    </div>
                    <div class="project-content">
                        <span class="project-difficulty advanced">고급</span>
                        <h3>음성 인식 제어</h3>
                        <p>음성 명령으로 제어하는 스마트 시스템</p>
                        <ul class="project-tech">
                            <li>음성 인식</li>
                            <li>AI 연동</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Resources Section -->
    <section class="section section-dark" id="resources">
        <div class="container">
            <h2 class="section-title">학습 자료</h2>
            <p class="section-subtitle">수업에 필요한 모든 자료를 한 곳에서</p>

            <div class="resources-grid">
                <div class="resource-card">
                    <div class="resource-icon">📚</div>
                    <h3>강의 자료</h3>
                    <p>주차별 PPT, PDF 강의노트</p>
                    <a href="#" class="resource-link">다운로드 →</a>
                </div>
                <div class="resource-card">
                    <div class="resource-icon">💻</div>
                    <h3>예제 코드</h3>
                    <p>실습 예제 및 프로젝트 소스코드</p>
                    <a href="#" class="resource-link">GitHub →</a>
                </div>
                <div class="resource-card">
                    <div class="resource-icon">🎥</div>
                    <h3>동영상 강의</h3>
                    <p>실습 과정 동영상 튜토리얼</p>
                    <a href="#" class="resource-link">시청하기 →</a>
                </div>
                <div class="resource-card">
                    <div class="resource-icon">📖</div>
                    <h3>참고 문서</h3>
                    <p>데이터시트, 라이브러리 문서</p>
                    <a href="#" class="resource-link">보기 →</a>
                </div>
                <div class="resource-card">
                    <div class="resource-icon">🛠️</div>
                    <h3>개발 도구</h3>
                    <p>Arduino IDE, 시뮬레이터 등</p>
                    <a href="#" class="resource-link">다운로드 →</a>
                </div>
                <div class="resource-card">
                    <div class="resource-icon">❓</div>
                    <h3>Q&A 게시판</h3>
                    <p>질문과 답변, 토론</p>
                    <a href="#" class="resource-link">참여하기 →</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Schedule Section -->
    <section class="section" id="schedule">
        <div class="container">
            <h2 class="section-title">수업 일정</h2>
            <p class="section-subtitle">2026년 1학기 수업 스케줄</p>

            <div class="schedule-container">
                <div class="schedule-info">
                    <div class="info-item">
                        <div class="info-label">수업 시간</div>
                        <div class="info-value">매주 화요일 13:00 - 16:00</div>
                    </div>
                    <div class="info-item">
                        <div class="info-label">수업 장소</div>
                        <div class="info-value">전자실습실 (3층 301호)</div>
                    </div>
                    <div class="info-item">
                        <div class="info-label">담당 교사</div>
                        <div class="info-value">김선생님 (kim@school.ac.kr)</div>
                    </div>
                    <div class="info-item">
                        <div class="info-label">평가 방법</div>
                        <div class="info-value">실습 60% + 프로젝트 30% + 출석 10%</div>
                    </div>
                </div>

                <div class="schedule-calendar">
                    <h3>주요 일정</h3>
                    <div class="calendar-events">
                        <div class="event-item">
                            <div class="event-date">3월 4일</div>
                            <div class="event-details">
                                <div class="event-title">개강 및 OT</div>
                                <div class="event-desc">수업 소개, 실습실 안전교육</div>
                            </div>
                        </div>
                        <div class="event-item">
                            <div class="event-date">4월 15일</div>
                            <div class="event-details">
                                <div class="event-title">중간 프로젝트 발표</div>
                                <div class="event-desc">초급 과정 종합 프로젝트</div>
                            </div>
                        </div>
                        <div class="event-item">
                            <div class="event-date">5월 20일</div>
                            <div class="event-details">
                                <div class="event-title">IoT 해커톤</div>
                                <div class="event-desc">24시간 팀 프로젝트 대회</div>
                            </div>
                        </div>
                        <div class="event-item">
                            <div class="event-date">6월 24일</div>
                            <div class="event-details">
                                <div class="event-title">최종 프로젝트 발표</div>
                                <div class="event-desc">학기말 종합 프로젝트 시연</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h4>마이크로컨트롤러 제어</h4>
                    <p>미래를 만드는 기술, 함께 배워요</p>
                </div>
                <div class="footer-section">
                    <h4>빠른 링크</h4>
                    <ul>
                        <li><a href="#curriculum">커리큘럼</a></li>
                        <li><a href="#projects">프로젝트</a></li>
                        <li><a href="#resources">학습자료</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h4>문의</h4>
                    <p>📧 kim@school.ac.kr</p>
                    <p>📞 02-1234-5678</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2026 공업고등학교 전자과. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>

</html>
