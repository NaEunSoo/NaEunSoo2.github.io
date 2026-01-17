# 마이크로 컨트롤러 제어 개요
> 공업고등학교 교육과정 - Arduino와 ESP32를 활용한 실전 제어 시스템 구축

---

## 📊 과정 개요

| 항목 | 내용 |
|------|------|
| **핵심 목표** | 3가지 |
| **활용 센서** | 10+ 종류 |
| **실습 비중** | 100% |

---

## 🎯 1. 프로젝트 목표

마이크로 컨트롤러 제어를 통해 달성하고자 하는 핵심 역량

### 1.1 제어 개념 이해

디지털 신호와 아날로그 신호의 차이를 이해하고, 입력-처리-출력의 기본 제어 흐름을 학습합니다. PWM, 인터럽트, 타이머 등 핵심 제어 기법을 실습을 통해 체득합니다.

**학습 내용:**
- ▸ 디지털/아날로그 신호 처리
- ▸ PWM 제어 기법
- ▸ 인터럽트 및 타이머 활용
- ▸ 시리얼 통신 이해

### 1.2 센서·액추에이터 활용

다양한 센서로 환경 데이터를 수집하고, 액추에이터를 통해 물리적 제어를 수행합니다. 실제 산업 현장에서 사용되는 부품들을 직접 다루며 실무 감각을 키웁니다.

**학습 내용:**
- ▸ 온습도, 거리, 조도 센서 활용
- ▸ 모터, LED, 서보 제어
- ▸ 센서 데이터 분석 및 처리
- ▸ 액추에이터 정밀 제어

### 1.3 문제해결 및 협업 능력 강화

실제 문제 상황을 분석하고 해결하는 과정을 통해 논리적 사고력을 기릅니다. 팀 프로젝트를 통해 협업 능력과 의사소통 능력을 향상시킵니다.

**학습 내용:**
- ▸ 문제 분석 및 설계 능력
- ▸ 디버깅 및 트러블슈팅
- ▸ 팀 프로젝트 수행
- ▸ 기술 문서 작성

---

## 🔧 2. 활용 기술

프로젝트에서 사용하는 마이크로 컨트롤러와 센서 모듈

### 2.1 마이크로 컨트롤러 유닛 (MCU)

#### Arduino Uno 🟢 입문용
가장 널리 사용되는 입문용 보드로, 풍부한 라이브러리와 커뮤니티 지원이 특징입니다.

**사양:**
- **MCU:** ATmega328P
- **동작 전압:** 5V
- **디지털 I/O:** 14핀
- **아날로그 입력:** 6핀
- **플래시 메모리:** 32KB

#### Arduino Nano 🔵 소형
Uno와 동일한 기능을 소형 폼팩터로 제공하여 공간이 제한된 프로젝트에 적합합니다.

**사양:**
- **MCU:** ATmega328P
- **동작 전압:** 5V
- **디지털 I/O:** 14핀
- **아날로그 입력:** 8핀
- **크기:** 18mm × 45mm

#### ESP32 🔴 IoT
WiFi와 Bluetooth를 내장한 강력한 MCU로, IoT 프로젝트에 최적화되어 있습니다.

**사양:**
- **MCU:** Xtensa 32-bit LX6
- **동작 전압:** 3.3V
- **WiFi:** 802.11 b/g/n
- **Bluetooth:** v4.2 BR/EDR & BLE
- **플래시 메모리:** 4MB

#### ESP8266 🟡 WiFi
저렴한 가격의 WiFi 모듈로, 간단한 IoT 프로젝트에 적합합니다.

**사양:**
- **MCU:** Tensilica L106 32-bit
- **동작 전압:** 3.3V
- **WiFi:** 802.11 b/g/n
- **GPIO:** 17핀
- **플래시 메모리:** 4MB

---

### 2.2 센서 및 모듈

#### 🌡️ DHT11/DHT22 - 온습도 센서
온도와 습도를 동시에 측정하는 디지털 센서

#### 📏 HC-SR04 - 초음파 거리 센서
2cm~400cm 범위의 거리를 측정

#### ☀️ CDS 포토셀 - 조도 센서
주변 밝기를 감지하는 아날로그 센서

#### 👤 PIR 센서 - 인체 감지 센서
적외선으로 움직임을 감지

#### ⏰ DS3231 - RTC 모듈
정밀한 시간 관리를 위한 실시간 시계

#### 📺 LCD 1602 - 문자 디스플레이
16x2 문자를 표시하는 LCD

#### 🔄 서보 모터 - 액추에이터
정밀한 각도 제어가 가능한 모터

#### 💡 RGB LED - 출력 장치
다양한 색상을 표현하는 LED

#### 🔊 부저 - 음향 출력
소리를 출력하는 피에조 부저

#### ⌨️ 키패드 4x4 - 입력 장치
16개 버튼으로 입력을 받는 키패드

---

## 📦 3. 산출물

프로젝트 완료 시 제출해야 할 결과물

### 3.1 회로도

프로젝트의 하드웨어 구성을 명확하게 보여주는 회로도를 작성합니다. Fritzing, TinkerCAD, 또는 KiCAD 등의 도구를 활용할 수 있습니다.

#### 포함 사항
✓ 브레드보드 배선도 (Breadboard View)  
✓ 회로 구성도 (Schematic View)  
✓ 부품 목록 (Bill of Materials)  
✓ 연결 핀 번호 및 설명

#### 권장 도구
- `Fritzing` - 직관적인 회로도 작성 도구
- `TinkerCAD Circuits` - 온라인 시뮬레이터
- `KiCAD` - 전문가용 PCB 설계 도구
- `EasyEDA` - 웹 기반 회로 설계 도구

---

### 3.2 소스코드

마이크로 컨트롤러를 제어하는 프로그램 코드를 작성합니다. 코드는 가독성이 높고 주석이 충분히 포함되어야 합니다.

#### 포함 사항
✓ 주석이 포함된 소스코드 (.ino 또는 .cpp)  
✓ 코드 설명 문서 (README.md)  
✓ 사용된 라이브러리 목록  
✓ 업로드 및 실행 방법

#### 코드 작성 예시

```cpp
// DHT11 온습도 센서 제어 예제
#include <DHT.h>

#define DHTPIN 2      // DHT11 데이터 핀
#define DHTTYPE DHT11 // 센서 타입

DHT dht(DHTPIN, DHTTYPE);

void setup() {
  Serial.begin(9600);
  dht.begin();
  Serial.println("DHT11 센서 초기화 완료");
}

void loop() {
  float humidity = dht.readHumidity();
  float temperature = dht.readTemperature();
  
  if (isnan(humidity) || isnan(temperature)) {
    Serial.println("센서 읽기 실패!");
    return;
  }
  
  Serial.print("습도: ");
  Serial.print(humidity);
  Serial.print("% | 온도: ");
  Serial.print(temperature);
  Serial.println("°C");
  
  delay(2000);
}
```

---

### 3.3 추가 산출물 (선택사항)

#### 🎥 시연 영상
프로젝트 동작을 보여주는 영상

#### 📄 프로젝트 보고서
개발 과정과 결과를 정리한 문서

#### 📸 실물 사진
완성된 하드웨어의 사진

#### 📊 발표 자료
프로젝트를 설명하는 PPT 또는 PDF

---

## 💡 4. 예제 프로젝트

학습 단계별 추천 프로젝트

### 🟢 초급: 스마트 온도계

DHT11 센서로 온습도를 측정하고 LCD에 표시하는 프로젝트입니다. 일정 온도 이상이 되면 LED가 켜지고 부저가 울립니다.

**사용 기술:**
- Arduino Uno
- DHT11
- LCD 1602
- LED

**학습 내용:**
- 디지털 센서 데이터 읽기
- LCD 문자 출력
- 조건문을 이용한 제어

---

### 🟡 중급: 자동 조명 시스템

조도 센서와 PIR 센서를 활용하여 어두울 때 사람이 감지되면 자동으로 LED가 켜지는 시스템입니다.

**사용 기술:**
- Arduino Nano
- CDS 센서
- PIR 센서
- RGB LED

**학습 내용:**
- 아날로그 센서 값 처리
- 다중 센서 통합
- PWM을 이용한 LED 밝기 조절

---

### 🔴 고급: IoT 환경 모니터링

ESP32를 사용하여 온습도, 조도 데이터를 수집하고 WiFi를 통해 웹 서버로 전송하여 실시간 모니터링합니다.

**사용 기술:**
- ESP32
- DHT22
- CDS 센서
- WiFi

**학습 내용:**
- WiFi 연결 및 통신
- 웹 서버 구축
- JSON 데이터 전송
- 실시간 데이터 시각화

---

## 📚 5. 학습 자료

### 공식 문서 및 도구

#### 📖 [Arduino 공식 문서](https://www.arduino.cc/reference/ko/)
함수 레퍼런스 및 튜토리얼

#### 🔧 [TinkerCAD Circuits](https://www.tinkercad.com/circuits)
온라인 회로 시뮬레이터

#### ⚡ [Fritzing](https://fritzing.org/)
회로도 작성 도구

#### 🎥 [YouTube 튜토리얼](https://www.youtube.com/results?search_query=arduino+tutorial+korean)
동영상 강의 자료

---

## 📋 부록

### A. 프로젝트 체크리스트

- [ ] 프로젝트 목표 설정
- [ ] MCU 및 센서 선정
- [ ] 회로도 작성
- [ ] 브레드보드 구성
- [ ] 소스코드 작성
- [ ] 테스트 및 디버깅
- [ ] 문서화
- [ ] 발표 준비

### B. 안전 수칙

⚠️ **전기 안전**
- 전원을 연결하기 전 회로를 재확인하세요
- 5V와 3.3V 전압을 혼동하지 마세요
- 단락(Short Circuit)에 주의하세요

⚠️ **부품 취급**
- 정전기 방지를 위해 손을 씻으세요
- IC 칩은 핀을 구부리지 않도록 조심하세요
- 극성이 있는 부품(LED, 전해 콘덴서)의 방향을 확인하세요

### C. 트러블슈팅 가이드

#### 문제: 업로드 실패
**해결 방법:**
1. USB 케이블 연결 확인
2. 올바른 보드 선택 (도구 > 보드)
3. 올바른 포트 선택 (도구 > 포트)
4. 드라이버 설치 확인

#### 문제: 센서 값이 이상함
**해결 방법:**
1. 배선 연결 재확인
2. 전원 전압 확인
3. 풀업/풀다운 저항 확인
4. 센서 데이터시트 참조

#### 문제: 코드가 작동하지 않음
**해결 방법:**
1. 시리얼 모니터로 디버깅
2. 라이브러리 설치 확인
3. 변수 초기화 확인
4. 논리 오류 점검

---

## 📞 문의 및 지원

프로젝트 진행 중 문제가 발생하면:
- 담당 교사에게 문의
- Arduino 공식 포럼 활용
- 온라인 커뮤니티 참여 (네이버 카페, 디스코드 등)

---

## 📄 라이선스

이 문서는 교육 목적으로 제작되었습니다.

**© 2026 공업고등학교 마이크로 컨트롤러 제어 과정**

Made with ❤️ for education.

---

### 문서 정보

- **작성일:** 2026-01-17
- **버전:** 1.0
- **대상:** 공업고등학교 학생
- **과목:** 마이크로 컨트롤러 제어

---

## 🔖 빠른 참조

| 항목 | 설명 |
|------|------|
| **Arduino IDE** | https://www.arduino.cc/en/software |
| **ESP32 보드 매니저** | https://dl.espressif.com/dl/package_esp32_index.json |
| **DHT 라이브러리** | Adafruit DHT sensor library |
| **LCD 라이브러리** | LiquidCrystal_I2C |
| **서보 라이브러리** | Servo.h (내장) |

---

**끝.**
// Smooth scroll for navigation links
document.querySelectorAll('.nav-link').forEach(link => {
    link.addEventListener('click', function(e) {
        e.preventDefault();
        const targetId = this.getAttribute('href');
        const targetSection = document.querySelector(targetId);
        
        if (targetSection) {
            const navHeight = document.querySelector('.nav-bar').offsetHeight;
            const targetPosition = targetSection.offsetTop - navHeight;
            
            window.scrollTo({
                top: targetPosition,
                behavior: 'smooth'
            });
        }
    });
});

// Active navigation link on scroll
const sections = document.querySelectorAll('.section');
const navLinks = document.querySelectorAll('.nav-link');

function updateActiveLink() {
    const scrollPosition = window.scrollY + 150;
    
    sections.forEach(section => {
        const sectionTop = section.offsetTop;
        const sectionHeight = section.offsetHeight;
        const sectionId = section.getAttribute('id');
        
        if (scrollPosition >= sectionTop && scrollPosition < sectionTop + sectionHeight) {
            navLinks.forEach(link => {
                link.classList.remove('active');
                if (link.getAttribute('href') === `#${sectionId}`) {
                    link.classList.add('active');
                }
            });
        }
    });
}

window.addEventListener('scroll', updateActiveLink);

// Intersection Observer for fade-in animations
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.style.opacity = '1';
            entry.target.style.transform = 'translateY(0)';
        }
    });
}, observerOptions);

// Observe cards and elements for animation
const animatedElements = document.querySelectorAll('.goal-card, .tech-card, .sensor-card, .output-card, .example-card, .additional-item, .resource-link');

animatedElements.forEach((element, index) => {
    element.style.opacity = '0';
    element.style.transform = 'translateY(30px)';
    element.style.transition = `opacity 0.6s ease-out ${index * 0.1}s, transform 0.6s ease-out ${index * 0.1}s`;
    observer.observe(element);
});

// Counter animation for hero stats
function animateCounter(element, target, duration = 2000) {
    let start = 0;
    const increment = target / (duration / 16);
    
    const timer = setInterval(() => {
        start += increment;
        if (start >= target) {
            element.textContent = target;
            clearInterval(timer);
        } else {
            element.textContent = Math.floor(start);
        }
    }, 16);
}

// Trigger counter animation when hero is visible
const heroObserver = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            const statNumbers = document.querySelectorAll('.stat-number');
            statNumbers.forEach(stat => {
                const text = stat.textContent;
                const number = parseInt(text);
                if (!isNaN(number)) {
                    stat.textContent = '0';
                    animateCounter(stat, number);
                }
            });
            heroObserver.unobserve(entry.target);
        }
    });
}, { threshold: 0.5 });

const hero = document.querySelector('.hero');
if (hero) {
    heroObserver.observe(hero);
}

// Parallax effect for hero background
window.addEventListener('scroll', () => {
    const scrolled = window.pageYOffset;
    const heroBackground = document.querySelector('.hero-background');
    
    if (heroBackground && scrolled < window.innerHeight) {
        heroBackground.style.transform = `translateY(${scrolled * 0.5}px)`;
    }
});

// Add hover effect sound (optional - can be enabled with audio files)
const cards = document.querySelectorAll('.goal-card, .tech-card, .sensor-card, .output-card, .example-card');

cards.forEach(card => {
    card.addEventListener('mouseenter', function() {
        this.style.transition = 'all 0.3s cubic-bezier(0.4, 0, 0.2, 1)';
    });
});

// Copy code to clipboard functionality
const codeBlocks = document.querySelectorAll('.code-example pre');

codeBlocks.forEach(block => {
    const button = document.createElement('button');
    button.className = 'copy-button';
    button.innerHTML = `
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <rect x="9" y="9" width="13" height="13" rx="2" ry="2"></rect>
            <path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"></path>
        </svg>
        복사
    `;
    
    button.style.cssText = `
        position: absolute;
        top: 10px;
        right: 10px;
        background: rgba(102, 126, 234, 0.9);
        color: white;
        border: none;
        padding: 8px 12px;
        border-radius: 6px;
        cursor: pointer;
        font-size: 0.875rem;
        display: flex;
        align-items: center;
        gap: 6px;
        transition: all 0.2s;
        font-family: 'Noto Sans KR', sans-serif;
    `;
    
    button.querySelector('svg').style.cssText = `
        width: 16px;
        height: 16px;
    `;
    
    block.parentElement.style.position = 'relative';
    block.parentElement.appendChild(button);
    
    button.addEventListener('click', async () => {
        const code = block.querySelector('code').textContent;
        
        try {
            await navigator.clipboard.writeText(code);
            button.innerHTML = `
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M5 13l4 4L19 7"></path>
                </svg>
                복사됨!
            `;
            button.style.background = 'rgba(74, 222, 128, 0.9)';
            
            setTimeout(() => {
                button.innerHTML = `
                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <rect x="9" y="9" width="13" height="13" rx="2" ry="2"></rect>
                        <path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"></path>
                    </svg>
                    복사
                `;
                button.style.background = 'rgba(102, 126, 234, 0.9)';
                button.querySelector('svg').style.cssText = `
                    width: 16px;
                    height: 16px;
                `;
            }, 2000);
        } catch (err) {
            console.error('Failed to copy code:', err);
        }
    });
    
    button.addEventListener('mouseenter', () => {
        button.style.background = 'rgba(102, 126, 234, 1)';
        button.style.transform = 'scale(1.05)';
    });
    
    button.addEventListener('mouseleave', () => {
        if (!button.textContent.includes('복사됨')) {
            button.style.background = 'rgba(102, 126, 234, 0.9)';
        }
        button.style.transform = 'scale(1)';
    });
});

// Add loading animation
window.addEventListener('load', () => {
    document.body.style.opacity = '0';
    setTimeout(() => {
        document.body.style.transition = 'opacity 0.5s ease-in';
        document.body.style.opacity = '1';
    }, 100);
});

// Navbar background change on scroll
const navbar = document.querySelector('.nav-bar');
let lastScroll = 0;

window.addEventListener('scroll', () => {
    const currentScroll = window.pageYOffset;
    
    if (currentScroll > 100) {
        navbar.style.boxShadow = '0 10px 30px rgba(0, 0, 0, 0.1)';
    } else {
        navbar.style.boxShadow = '0 4px 6px -1px rgba(0, 0, 0, 0.1)';
    }
    
    lastScroll = currentScroll;
});

// Add ripple effect to buttons and cards
function createRipple(event) {
    const button = event.currentTarget;
    const ripple = document.createElement('span');
    const rect = button.getBoundingClientRect();
    const size = Math.max(rect.width, rect.height);
    const x = event.clientX - rect.left - size / 2;
    const y = event.clientY - rect.top - size / 2;
    
    ripple.style.cssText = `
        position: absolute;
        width: ${size}px;
        height: ${size}px;
        border-radius: 50%;
        background: rgba(255, 255, 255, 0.3);
        left: ${x}px;
        top: ${y}px;
        transform: scale(0);
        animation: ripple 0.6s ease-out;
        pointer-events: none;
    `;
    
    button.style.position = 'relative';
    button.style.overflow = 'hidden';
    button.appendChild(ripple);
    
    setTimeout(() => ripple.remove(), 600);
}

// Add ripple animation CSS
const style = document.createElement('style');
style.textContent = `
    @keyframes ripple {
        to {
            transform: scale(4);
            opacity: 0;
        }
    }
`;
document.head.appendChild(style);

// Apply ripple to interactive elements
const interactiveElements = document.querySelectorAll('.goal-card, .tech-card, .sensor-card, .resource-link');
interactiveElements.forEach(element => {
    element.addEventListener('click', createRipple);
});

// Console message
console.log('%c마이크로 컨트롤러 제어 개요', 'font-size: 24px; font-weight: bold; color: #667eea;');
console.log('%c공업고등학교 교육과정', 'font-size: 14px; color: #64748b;');
console.log('%c\n이 페이지는 교육 목적으로 제작되었습니다.', 'font-size: 12px; color: #94a3b8;');

