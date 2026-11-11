[index.html](https://github.com/user-attachments/files/34671862/index.html)
<!DOCTYPE html>
<html lang="ko" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>국가대표목동태권도입시센터</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        dark: '#0b0b0b',
                        card: '#161616',
                        crimson: '#dc2626',
                        crimsonHover: '#b91c1c',
                    },
                    fontFamily: {
                        sans: ['Inter', 'Noto Sans KR', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&family=Noto+Sans+KR:wght@300;400;500;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', 'Noto Sans KR', sans-serif;
            background-color: #0b0b0b;
            color: #f3f4f6;
            overflow-x: hidden;
        }
        .glass-card {
            background: rgba(22, 22, 22, 0.8);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .glass-card:hover {
            border-color: rgba(220, 38, 38, 0.4);
        }
        .glow-red {
            box-shadow: 0 0 40px -10px rgba(220, 38, 38, 0.3);
        }
    </style>
</head>
<body class="bg-dark text-gray-100 antialiased selection:bg-crimson selection:text-white">

    <!-- Header / Nav -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-dark/90 backdrop-blur-md border-b border-white/10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-3 cursor-pointer" onclick="window.scrollTo({top:0, behavior:'smooth'})">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-crimson to-red-900 flex items-center justify-center text-white font-bold text-xl shadow-lg shadow-crimson/30">
                    <i class="fa-solid fa-shield-cat"></i>
                </div>
                <div>
                    <span class="block font-black text-sm sm:text-base tracking-tight text-white whitespace-nowrap">국가대표목동태권도입시센터</span>
                </div>
            </div>
            
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium text-gray-300">
                <a href="#about" class="hover:text-crimson transition">센터 소개</a>
                <a href="#coaches" class="hover:text-crimson transition">지도진 소개</a>
                <a href="#curriculum" class="hover:text-crimson transition">선수반 커리큘럼</a>
                <a href="#results" class="hover:text-crimson transition">합격 실적</a>
                <a href="#faq" class="hover:text-crimson transition">FAQ</a>
            </nav>

            <div class="flex items-center space-x-3">
                <a href="https://map.naver.com/p/entry/place/1571634881?placePath=%2Fhome%3Fentry%3Dplt%26from%3Dmap%26fromPanelNum%3D1%26additionalHeight%3D76%26timestamp%3D202611111305%26locale%3Dko%26svcName%3Dmap_pcv5&searchType=place&lng=127.1234931&lat=37.1821079&c=15.00,0,0,0,dh" target="_blank" class="hidden sm:inline-flex items-center justify-center px-4 py-2.5 rounded-full bg-crimson hover:bg-crimsonHover text-white font-bold text-xs transition shadow-lg shadow-crimson/30">
                    상담예약
                </a>
                <button id="mobile-menu-btn" class="md:hidden text-white p-2 focus:outline-none">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-card border-b border-white/10 px-6 py-4 space-y-3">
            <a href="#about" class="block text-gray-300 hover:text-crimson py-1">센터 소개</a>
            <a href="#coaches" class="block text-gray-300 hover:text-crimson py-1">지도진 소개</a>
            <a href="#curriculum" class="block text-gray-300 hover:text-crimson py-1">선수반 커리큘럼</a>
            <a href="#results" class="block text-gray-300 hover:text-crimson py-1">합격 실적</a>
            <a href="#faq" class="block text-gray-300 hover:text-crimson py-1">FAQ</a>
            <a href="https://map.naver.com/p/entry/place/1571634881?placePath=%2Fhome%3Fentry%3Dplt%26from%3Dmap%26fromPanelNum%3D1%26additionalHeight%3D76%26timestamp%3D202611111305%26locale%3Dko%26svcName%3Dmap_pcv5&searchType=place&lng=127.1234931&lat=37.1821079&c=15.00,0,0,0,dh" target="_blank" class="block w-full py-3 rounded-xl bg-crimson text-white font-bold text-sm text-center">
                상담예약
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative pt-36 pb-24 md:pt-48 md:pb-36 overflow-hidden flex flex-col items-center justify-center text-center">
        <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-96 h-96 bg-crimson/20 rounded-full blur-3xl pointer-events-none"></div>

        <div class="max-w-5xl mx-auto px-4 relative z-10">
            <div class="inline-flex items-center space-x-2 px-4 py-1.5 rounded-full bg-crimson/10 border border-crimson/30 text-crimson text-xs sm:text-sm font-semibold mb-6">
                <i class="fa-solid fa-bolt"></i>
                <span>화성시 경희대 출신 입시 전문가 그룹</span>
            </div>

            <!-- Hero Main Title cleanly aligned -->
            <h1 class="text-2xl sm:text-4xl md:text-5xl font-black tracking-tight text-white mb-6 leading-relaxed">
                도장에서 시작해, 대학으로 증명하다.<br>
                <span class="text-crimson">국가대표 목동태권도 입시센터</span>
            </h1>

            <p class="text-base sm:text-lg text-gray-400 max-w-2xl mx-auto mb-10 font-medium">
                진단 기반으로 훈련을 설계하고 결과로 검증하는 압도적인 입시 노하우를 경험하세요.
            </p>

            <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                <a href="https://map.naver.com/p/entry/place/1571634881?placePath=%2Fhome%3Fentry%3Dplt%26from%3Dmap%26fromPanelNum%3D1%26additionalHeight%3D76%26timestamp%3D202611111305%26locale%3Dko%26svcName%3Dmap_pcv5&searchType=place&lng=127.1234931&lat=37.1821079&c=15.00,0,0,0,dh" target="_blank" class="w-full sm:w-auto px-8 py-4 rounded-2xl bg-crimson hover:bg-crimsonHover text-white font-bold text-base transition shadow-lg shadow-crimson/40 flex items-center justify-center space-x-2">
                    <i class="fa-solid fa-calendar-check"></i>
                    <span>상담예약</span>
                </a>
                <a href="https://www.instagram.com/mokdong_taekwondo?exln=MjlueWVtZGY3YXVk" target="_blank" class="w-full sm:w-auto px-8 py-4 rounded-2xl glass-card text-white hover:border-crimson transition font-bold text-base flex items-center justify-center space-x-2">
                    <i class="fa-brands fa-instagram text-pink-500"></i>
                    <span>인스타그램 DM 상담</span>
                </a>
            </div>
        </div>
    </section>

    <!-- Philosophy & Intro Section -->
    <section id="about" class="py-24 bg-zinc-950 border-t border-white/5">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-crimson font-bold text-sm tracking-widest uppercase mb-2 block">Our Philosophy</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white mb-4">백문이 불여일견</h2>
                <blockquote class="text-xl sm:text-2xl italic text-gray-300 font-medium">
                    “백 번 듣는 것보다 한 번 직접 보는 것이 낫다”
                </blockquote>
            </div>

            <div class="glass-card p-8 sm:p-12 rounded-3xl max-w-4xl mx-auto text-center space-y-6 border-crimson/30">
                <p class="text-lg sm:text-xl font-bold text-white leading-relaxed">
                    진단 기반으로 훈련을 설계, 결과로 검증하는 <span class="text-crimson">목동태권도</span>의 노하우
                </p>
                <div class="pt-6 border-t border-white/10 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 text-left">
                    <div class="p-4 rounded-2xl bg-dark/50 border border-white/5">
                        <span class="block text-crimson font-bold mb-1 text-sm">전문 입시</span>
                        <p class="text-xs text-gray-300">전문 입시 선수단 지도 (2019년~)</p>
                    </div>
                    <div class="p-4 rounded-2xl bg-dark/50 border border-white/5">
                        <span class="block text-crimson font-bold mb-1 text-sm">동탄 유일</span>
                        <p class="text-xs text-gray-300">중고등 품새 선수 및 입시 체육 전문지도</p>
                    </div>
                    <div class="p-4 rounded-2xl bg-dark/50 border border-white/5">
                        <span class="block text-crimson font-bold mb-1 text-sm">초등 선수단</span>
                        <p class="text-xs text-gray-300">초등 품새 선수단 개별훈련</p>
                    </div>
                    <div class="p-4 rounded-2xl bg-dark/50 border border-white/5">
                        <span class="block text-crimson font-bold mb-1 text-sm">다양한 연령</span>
                        <p class="text-xs text-gray-300">아동 및 성인반 지도 (2019년~)</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Coaching Staff Section -->
    <section id="coaches" class="py-24 bg-dark border-t border-white/5">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-crimson font-bold text-sm tracking-widest uppercase mb-2 block">Professional Staff</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white">화성시 경희대 출신의 입시 전문가</h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- 감독 -->
                <div class="glass-card p-6 sm:p-8 rounded-3xl flex flex-col justify-between border-crimson/40">
                    <div>
                        <div class="w-12 h-12 rounded-2xl bg-crimson/20 flex items-center justify-center text-crimson text-xl font-bold mb-4">
                            <i class="fa-solid fa-user-tie"></i>
                        </div>
                        <span class="text-xs font-bold text-crimson tracking-widest uppercase">감독</span>
                        <h3 class="text-xl font-bold text-white mt-1 mb-4">입시 총괄 감독</h3>
                        <ul class="space-y-2 text-gray-300 text-xs">
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-crimson mt-0.5"></i><span>경희대학교 태권도학 박사 과정</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-crimson mt-0.5"></i><span>경희대학교 태권도학 석사 졸업</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-crimson mt-0.5"></i><span>한국 나사렛대학교 태권도학과 학사 졸업</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-crimson mt-0.5"></i><span>전국대회 공인 품새 부분 다수 입상</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-crimson mt-0.5"></i><span>아시아 태권도 품새 위원</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-crimson mt-0.5"></i><span>전) 대한 태권도 협회 격파 상임심판</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-crimson mt-0.5"></i><span>태권도 공인 6단</span></li>
                        </ul>
                    </div>
                </div>

                <!-- 품새 메인 코치 -->
                <div class="glass-card p-6 sm:p-8 rounded-3xl flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-2xl bg-blue-600/20 flex items-center justify-center text-blue-400 text-xl font-bold mb-4">
                            <i class="fa-solid fa-medal"></i>
                        </div>
                        <span class="text-xs font-bold text-blue-400 tracking-widest uppercase">품새 메인 코치</span>
                        <h3 class="text-xl font-bold text-white mt-1 mb-4">품새 전문 코치</h3>
                        <ul class="space-y-2 text-gray-300 text-xs">
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-blue-400 mt-0.5"></i><span>경희대학교 태권도학과 학사졸업</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-blue-400 mt-0.5"></i><span>전) 홍천군청 태권도 품새 실업팀 선수</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-blue-400 mt-0.5"></i><span>국가대표 태권도 선수권 대회 1위</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-blue-400 mt-0.5"></i><span>국가대표 춘천 아시아 태권도 선수권 대회 1위</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-blue-400 mt-0.5"></i><span>경찰청장기 전국태권도 선수권 1위</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-blue-400 mt-0.5"></i><span>한국실업태권도연맹회장기 공인품새 1위</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-blue-400 mt-0.5"></i><span>태권도 공인 5단</span></li>
                        </ul>
                    </div>
                </div>

                <!-- 겨루기 메인 코치 -->
                <div class="glass-card p-6 sm:p-8 rounded-3xl flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-2xl bg-amber-500/20 flex items-center justify-center text-amber-400 text-xl font-bold mb-4">
                            <i class="fa-solid fa-fire"></i>
                        </div>
                        <span class="text-xs font-bold text-amber-400 tracking-widest uppercase">겨루기 메인 코치</span>
                        <h3 class="text-xl font-bold text-white mt-1 mb-4">겨루기 전문 코치</h3>
                        <ul class="space-y-2 text-gray-300 text-xs">
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-amber-400 mt-0.5"></i><span>용인대학교 태권도학과 학사</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-amber-400 mt-0.5"></i><span>숙지고등학교 태권도부</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-amber-400 mt-0.5"></i><span>용인대학교 학군단</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-amber-400 mt-0.5"></i><span>태권도 공인 4단</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-amber-400 mt-0.5"></i><span>경기도 체육대회 겨루기 -58급 1위</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-amber-400 mt-0.5"></i><span>용인대 평가전 겨루기 개인전 1위</span></li>
                        </ul>
                    </div>
                </div>

                <!-- 시범 메인코치 -->
                <div class="glass-card p-6 sm:p-8 rounded-3xl flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-2xl bg-emerald-600/20 flex items-center justify-center text-emerald-400 text-xl font-bold mb-4">
                            <i class="fa-solid fa-bolt-lightning"></i>
                        </div>
                        <span class="text-xs font-bold text-emerald-400 tracking-widest uppercase">시범 메인코치</span>
                        <h3 class="text-xl font-bold text-white mt-1 mb-4">익스트림 & 시범</h3>
                        <ul class="space-y-2 text-gray-300 text-xs">
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-emerald-400 mt-0.5"></i><span>경희대학교 태권도학과 학사</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-emerald-400 mt-0.5"></i><span>태권도 공인 5단</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-emerald-400 mt-0.5"></i><span>국가대표 시범단 단원</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-emerald-400 mt-0.5"></i><span>경희대학교 익스트림 16대 단장</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-emerald-400 mt-0.5"></i><span>지상작전사령부 태권도시범단</span></li>
                            <li class="flex items-start space-x-2"><i class="fa-solid fa-check text-emerald-400 mt-0.5"></i><span>태권도 시범 대회 다수 입상</span></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Curriculum / League System Section -->
    <section id="curriculum" class="py-24 bg-zinc-950">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-crimson font-bold text-sm tracking-widest uppercase mb-2 block">League System</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white mb-4">선수반 운영 체계</h2>
                <p class="text-gray-400 max-w-xl mx-auto text-sm">C리그에서 기본을 잡고, B리그에서 실전을 익히며, A리그에서 실적으로 수렴합니다.</p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <!-- C리그 TEAM -->
                <div class="glass-card p-8 rounded-3xl flex flex-col justify-between">
                    <div>
                        <span class="text-xs font-bold text-blue-400 tracking-widest uppercase">C리그 TEAM</span>
                        <h3 class="text-2xl font-bold text-white mt-1 mb-2">입시 입문반</h3>
                        <p class="text-gray-400 text-sm mb-6 font-medium">흔들리지 않는 기본기 확립</p>
                        <ul class="space-y-3 text-sm text-gray-300">
                            <li class="flex items-center space-x-2"><i class="fa-solid fa-check text-blue-400"></i><span>기초 체력 훈련</span></li>
                            <li class="flex items-center space-x-2"><i class="fa-solid fa-check text-blue-400"></i><span>대회 기본기 확립</span></li>
                            <li class="flex items-center space-x-2"><i class="fa-solid fa-check text-blue-400"></i><span>180분 집중 훈련</span></li>
                        </ul>
                    </div>
                    <a href="https://map.naver.com/p/entry/place/1571634881?placePath=%2Fhome%3Fentry%3Dplt%26from%3Dmap%26fromPanelNum%3D1%26additionalHeight%3D76%26timestamp%3D202611111305%26locale%3Dko%26svcName%3Dmap_pcv5&searchType=place&lng=127.1234931&lat=37.1821079&c=15.00,0,0,0,dh" target="_blank" class="mt-8 block w-full py-3 rounded-xl bg-blue-600 hover:bg-blue-700 text-white font-bold text-sm text-center transition">
                        상담예약
                    </a>
                </div>

                <!-- B리그 TEAM -->
                <div class="glass-card p-8 rounded-3xl flex flex-col justify-between border-crimson/50 glow-red">
                    <div>
                        <span class="text-xs font-bold text-crimson tracking-widest uppercase">B리그 TEAM</span>
                        <h3 class="text-2xl font-bold text-white mt-1 mb-2">심화 훈련반</h3>
                        <p class="text-gray-400 text-sm mb-6 font-medium">전형별 맞춤 훈련반</p>
                        <ul class="space-y-3 text-sm text-gray-300">
                            <li class="flex items-center space-x-2"><i class="fa-solid fa-check text-crimson"></i><span>기술의 정확성, 표현성 향상</span></li>
                            <li class="flex items-center space-x-2"><i class="fa-solid fa-check text-crimson"></i><span>기량 극대화 및 숙련도 향상</span></li>
                            <li class="flex items-center space-x-2"><i class="fa-solid fa-check text-crimson"></i><span>전형 훈련 및 실전 대비</span></li>
                        </ul>
                    </div>
                    <a href="https://map.naver.com/p/entry/place/1571634881?placePath=%2Fhome%3Fentry%3Dplt%26from%3Dmap%26fromPanelNum%3D1%26additionalHeight%3D76%26timestamp%3D202611111305%26locale%3Dko%26svcName%3Dmap_pcv5&searchType=place&lng=127.1234931&lat=37.1821079&c=15.00,0,0,0,dh" target="_blank" class="mt-8 block w-full py-3 rounded-xl bg-crimson hover:bg-crimsonHover text-white font-bold text-sm text-center transition">
                        상담예약
                    </a>
                </div>

                <!-- A리그 TEAM -->
                <div class="glass-card p-8 rounded-3xl flex flex-col justify-between bg-gradient-to-br from-card to-zinc-900 border-amber-500/30">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="text-xs font-bold text-amber-400 tracking-widest uppercase">A리그 TEAM</span>
                            <span class="px-3 py-1 rounded-full bg-amber-500/20 text-amber-400 font-bold text-xs">Top Elite</span>
                        </div>
                        <h3 class="text-2xl font-bold text-white mb-2">엘리트 전문 선수반</h3>
                        <p class="text-gray-400 text-sm mb-6 font-medium">정식 선수 등록 후 전국대회 출전</p>
                        <ul class="space-y-3 text-sm text-gray-300">
                            <li class="flex items-center space-x-2"><i class="fa-solid fa-check text-amber-400"></i><span>전국 대회 출전 및 커리어 관리</span></li>
                            <li class="flex items-center space-x-2"><i class="fa-solid fa-check text-amber-400"></i><span>실전 시뮬레이션 및 멘탈 관리</span></li>
                            <li class="flex items-center space-x-2"><i class="fa-solid fa-check text-amber-400"></i><span>대회 영상 피드백 제공</span></li>
                            <li class="flex items-center space-x-2"><i class="fa-solid fa-check text-amber-400"></i><span>학생부 및 학업 성적 관리</span></li>
                        </ul>
                    </div>
                    <a href="https://map.naver.com/p/entry/place/1571634881?placePath=%2Fhome%3Fentry%3Dplt%26from%3Dmap%26fromPanelNum%3D1%26additionalHeight%3D76%26timestamp%3D202611111305%26locale%3Dko%26svcName%3Dmap_pcv5&searchType=place&lng=127.1234931&lat=37.1821079&c=15.00,0,0,0,dh" target="_blank" class="mt-8 block w-full py-3 rounded-xl bg-amber-500 hover:bg-amber-600 text-dark font-bold text-sm text-center transition">
                        상담예약
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Track Record Section -->
    <section id="results" class="py-24 bg-dark border-t border-white/5">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <span class="text-crimson font-bold text-sm tracking-widest uppercase mb-2 block">Records</span>
            <h2 class="text-3xl sm:text-4xl font-extrabold text-white mb-4">누적 합격 실적</h2>
            <p class="text-gray-400 mb-12">지도진이 배출한 자랑스러운 합격의 기록입니다.</p>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 max-w-5xl mx-auto">
                <div class="glass-card p-6 rounded-2xl flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-xl bg-red-600/20 text-red-500 flex items-center justify-center font-black text-lg">경희</div>
                    <div class="text-left">
                        <h4 class="text-base font-bold text-white">경희대학교</h4>
                        <p class="text-gray-400 text-xs">태권도학과</p>
                    </div>
                </div>
                <div class="glass-card p-6 rounded-2xl flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-2xl bg-blue-500/20 text-blue-300 flex items-center justify-center font-black text-lg">용인</div>
                    <div class="text-left">
                        <h4 class="text-base font-bold text-white">용인대학교</h4>
                        <p class="text-gray-400 text-xs">태권도학과</p>
                    </div>
                </div>
                <div class="glass-card p-6 rounded-2xl flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-2xl bg-indigo-600/20 text-indigo-400 flex items-center justify-center font-black text-lg">백석</div>
                    <div class="text-left">
                        <h4 class="text-base font-bold text-white">백석대학교</h4>
                        <p class="text-gray-400 text-xs">태권도학과</p>
                    </div>
                </div>
                <div class="glass-card p-6 rounded-2xl flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-2xl bg-amber-600/20 text-amber-400 flex items-center justify-center font-black text-lg">나사렛</div>
                    <div class="text-left">
                        <h4 class="text-base font-bold text-white">나사렛대학교</h4>
                        <p class="text-gray-400 text-xs">태권도학과</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="py-24 bg-zinc-950">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-crimson font-bold text-sm tracking-widest uppercase mb-2 block">FAQs</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white mb-4">자주 문의하시는 질문들</h2>
                <p class="text-gray-400">초등부 및 중·고등부 선수단 입시 관련 궁금증을 확인하세요.</p>
            </div>

            <!-- 초등부 선수단 FAQ Category -->
            <div class="mb-10">
                <h3 class="text-xl font-bold text-crimson mb-6 flex items-center space-x-2">
                    <i class="fa-solid fa-graduation-cap"></i>
                    <span>초등부 선수단</span>
                </h3>
                <div class="space-y-4">
                    <div class="glass-card rounded-2xl overflow-hidden transition">
                        <button onclick="toggleFaq('elem-1')" class="w-full px-6 py-5 text-left font-bold text-white flex justify-between items-center focus:outline-none">
                            <span>Q. 몇 학년부터 팀에 입단 가능한가요?</span>
                            <i id="faq-icon-elem-1" class="fa-solid fa-chevron-down transition-transform duration-300"></i>
                        </button>
                        <div id="faq-content-elem-1" class="hidden px-6 pb-5 text-gray-400 text-sm leading-relaxed border-t border-white/5 pt-4">
                            초등학교 1학년부터 6학년까지 입단할 수 있으며, 태권도 1품 이상을 취득한 학생에 한해 신청 가능합니다. 입단 전 체험 수업을 통해 기본기와 훈련 적응도를 확인한 후 입단을 결정합니다.
                        </div>
                    </div>

                    <div class="glass-card rounded-2xl overflow-hidden transition">
                        <button onclick="toggleFaq('elem-2')" class="w-full px-6 py-5 text-left font-bold text-white flex justify-between items-center focus:outline-none">
                            <span>Q. 일반 수련반과 선수단은 어떤 점이 다른가요?</span>
                            <i id="faq-icon-elem-2" class="fa-solid fa-chevron-down transition-transform duration-300"></i>
                        </button>
                        <div id="faq-content-elem-2" class="hidden px-6 pb-5 text-gray-400 text-sm leading-relaxed border-t border-white/5 pt-4">
                            일반 수련반과 선수단은 수련의 목표와 훈련 방향에 차이가 있습니다. 초등부 선수단은 생활체육을 넘어 엘리트 선수로 성장하고, 전국대회에 도전하는 것을 목표로 훈련합니다. 이를 위해 기본기부터 경기 기술까지 단계적으로 지도합니다.
                        </div>
                    </div>

                    <div class="glass-card rounded-2xl overflow-hidden transition">
                        <button onclick="toggleFaq('elem-3')" class="w-full px-6 py-5 text-left font-bold text-white flex justify-between items-center focus:outline-none">
                            <span>Q. 대회는 언제부터 출전하며, 출전 기준은 어떻게 되나요?</span>
                            <i id="faq-icon-elem-3" class="fa-solid fa-chevron-down transition-transform duration-300"></i>
                        </button>
                        <div id="faq-content-elem-3" class="hidden px-6 pb-5 text-gray-400 text-sm leading-relaxed border-t border-white/5 pt-4">
                            지도진이 학생의 실력과 준비 상태를 종합적으로 판단하여 출전을 결정합니다. 생활체육대회를 통해 경기 경험을 쌓고, 전국대회에 도전할 수 있는 경기력이 갖춰지면 지도진의 판단에 따라 출전 무대를 넓혀갑니다.
                        </div>
                    </div>

                    <div class="glass-card rounded-2xl overflow-hidden transition">
                        <button onclick="toggleFaq('elem-4')" class="w-full px-6 py-5 text-left font-bold text-white flex justify-between items-center focus:outline-none">
                            <span>Q. 아이의 훈련 성장 과정을 학부모가 확인할 수 있나요?</span>
                            <i id="faq-icon-elem-4" class="fa-solid fa-chevron-down transition-transform duration-300"></i>
                        </button>
                        <div id="faq-content-elem-4" class="hidden px-6 pb-5 text-gray-400 text-sm leading-relaxed border-t border-white/5 pt-4">
                            네, 대회에 출전할 때마다 경기 영상을 촬영하여 학부모님께 공유해 드립니다. 대회별 경기 모습을 통해 아이의 변화와 보완점을 확인하고, 경험이 쌓이면서 실력이 어떻게 성장해 가는지 함께 지켜보실 수 있습니다.
                        </div>
                    </div>

                    <div class="glass-card rounded-2xl overflow-hidden transition">
                        <button onclick="toggleFaq('elem-5')" class="w-full px-6 py-5 text-left font-bold text-white flex justify-between items-center focus:outline-none">
                            <span>Q. 입단 전 체험 수업이나 상담이 가능한가요?</span>
                            <i id="faq-icon-elem-5" class="fa-solid fa-chevron-down transition-transform duration-300"></i>
                        </button>
                        <div id="faq-content-elem-5" class="hidden px-6 pb-5 text-gray-400 text-sm leading-relaxed border-t border-white/5 pt-4">
                            네, 입단 전 상담과 3일간의 체험 수업이 가능합니다. 체험 기간에는 지도진이 학생의 기본기와 훈련 적응도를 확인하며, 학생도 선수단 훈련을 직접 경험하면서 훈련 강도와 자신의 의지를 점검할 수 있습니다. 이 과정을 바탕으로 입단 여부를 결정합니다.
                        </div>
                    </div>
                </div>
            </div>

            <!-- 중·고등부 선수단 FAQ Category -->
            <div>
                <h3 class="text-xl font-bold text-crimson mb-6 flex items-center space-x-2">
                    <i class="fa-solid fa-award"></i>
                    <span>중·고등부 선수단</span>
                </h3>
                <div class="space-y-4">
                    <div class="glass-card rounded-2xl overflow-hidden transition">
                        <button onclick="toggleFaq('high-1')" class="w-full px-6 py-5 text-left font-bold text-white flex justify-between items-center focus:outline-none">
                            <span>Q. 선수 경력이 없거나 늦게 시작해도 입단할 수 있나요?</span>
                            <i id="faq-icon-high-1" class="fa-solid fa-chevron-down transition-transform duration-300"></i>
                        </button>
                        <div id="faq-content-high-1" class="hidden px-6 pb-5 text-gray-400 text-sm leading-relaxed border-t border-white/5 pt-4">
                            네, 선수 경력이 없거나 늦게 시작한 학생도 입단할 수 있습니다. 현재의 실력과 준비 상태를 확인하고, 목표에 맞춰 기초부터 단계적으로 훈련합니다. 선수 경력뿐 아니라 앞으로 배우고 성장하려는 의지를 중요하게 생각합니다.
                        </div>
                    </div>

                    <div class="glass-card rounded-2xl overflow-hidden transition">
                        <button onclick="toggleFaq('high-2')" class="w-full px-6 py-5 text-left font-bold text-white flex justify-between items-center focus:outline-none">
                            <span>Q. 개인별 실력과 목표에 맞춘 훈련을 받을 수 있나요?</span>
                            <i id="faq-icon-high-2" class="fa-solid fa-chevron-down transition-transform duration-300"></i>
                        </button>
                        <div id="faq-content-high-2" class="hidden px-6 pb-5 text-gray-400 text-sm leading-relaxed border-t border-white/5 pt-4">
                            네, 학생의 실력과 목표 대학에 맞춰 맞춤형 수업을 진행합니다. 수시·정시 모집과 실기·입상 실적을 활용하는 전형 등 다양한 진학 방향을 함께 검토하고, 학생에게 적합한 준비 계획을 세워 지도합니다.
                        </div>
                    </div>

                    <div class="glass-card rounded-2xl overflow-hidden transition">
                        <button onclick="toggleFaq('high-3')" class="w-full px-6 py-5 text-left font-bold text-white flex justify-between items-center focus:outline-none">
                            <span>Q. 태권도 관련 대학 진학을 목표로 준비할 수 있나요?</span>
                            <i id="faq-icon-high-3" class="fa-solid fa-chevron-down transition-transform duration-300"></i>
                        </button>
                        <div id="faq-content-high-3" class="hidden px-6 pb-5 text-gray-400 text-sm leading-relaxed border-t border-white/5 pt-4">
                            네, 경희대학교, 용인대학교, 한국체육대학교, 가천대학교, 신한대학교, 백석대학교, 나사렛대학교, 계명대학교, 동아대학교, 우석대학교 등 태권도 관련 학과 진학을 목표로 준비합니다. 학생의 희망 대학과 준비 상황을 바탕으로 진학 방향을 설정하며, 지원 시점의 대학별 모집요강에 맞춰 준비합니다.
                        </div>
                    </div>

                    <div class="glass-card rounded-2xl overflow-hidden transition">
                        <button onclick="toggleFaq('high-4')" class="w-full px-6 py-5 text-left font-bold text-white flex justify-between items-center focus:outline-none">
                            <span>Q. 대회 입상 경력이 없어도 대학 입시를 준비할 수 있나요?</span>
                            <i id="faq-icon-high-4" class="fa-solid fa-chevron-down transition-transform duration-300"></i>
                        </button>
                        <div id="faq-content-high-4" class="hidden px-6 pb-5 text-gray-400 text-sm leading-relaxed border-t border-white/5 pt-4">
                            네, 대회 입상 경력이 없어도 대학 입시를 준비할 수 있습니다. 입상 실적을 요구하지 않는 실기 중심 전형을 목표로, 지원 대학의 평가 기준에 맞춰 내신·학교생활기록부와 실기를 준비합니다. 겨루기·품새·시범·발차기 등 실기 준비 항목은 대학과 전형에 따라 달라지므로, 해당 모집요강을 기준으로 지도합니다.
                        </div>
                    </div>

                    <div class="glass-card rounded-2xl overflow-hidden transition">
                        <button onclick="toggleFaq('high-5')" class="w-full px-6 py-5 text-left font-bold text-white flex justify-between items-center focus:outline-none">
                            <span>Q. 정규 훈련 외에 주말 훈련이나 방학 집중 훈련도 있나요?</span>
                            <i id="faq-icon-high-5" class="fa-solid fa-chevron-down transition-transform duration-300"></i>
                        </button>
                        <div id="faq-content-high-5" class="hidden px-6 pb-5 text-gray-400 text-sm leading-relaxed border-t border-white/5 pt-4">
                            네, 정규 훈련 외에도 주말 훈련과 방학 기간을 활용한 강화훈련을 진행합니다. 대회 및 입시 준비 일정에 맞춰 훈련을 계획하고, 집중적인 연습을 통해 부족한 부분을 보완합니다.
                        </div>
                    </div>

                    <div class="glass-card rounded-2xl overflow-hidden transition">
                        <button onclick="toggleFaq('high-6')" class="w-full px-6 py-5 text-left font-bold text-white flex justify-between items-center focus:outline-none">
                            <span>Q. 대회 참가·전지훈련 등에 필요한 훈련이 있나요?</span>
                            <i id="faq-icon-high-6" class="fa-solid fa-chevron-down transition-transform duration-300"></i>
                        </button>
                        <div id="faq-content-high-6" class="hidden px-6 pb-5 text-gray-400 text-sm leading-relaxed border-t border-white/5 pt-4">
                            네, 대회 준비를 위한 강화훈련을 진행하며, 동계훈련은 전지훈련으로 운영합니다. 집중적인 훈련을 통해 체력과 기술을 보완하고, 다음 시즌의 대회와 입시를 준비합니다.
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark border-t border-white/10 py-12 text-gray-500 text-sm text-center">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 space-y-4">
            <div class="flex items-center justify-center space-x-2">
                <div class="w-8 h-8 rounded-lg bg-crimson flex items-center justify-center text-white font-bold text-sm">
                    <i class="fa-solid fa-shield-cat"></i>
                </div>
                <span class="font-bold text-white text-base">국가대표목동태권도입시센터</span>
            </div>
            <p>태권도로 대학을 가는 아이는 전략부터 다릅니다.</p>
            <div class="flex justify-center space-x-4 pt-2">
                <a href="https://map.naver.com/p/entry/place/1571634881?placePath=%2Fhome%3Fentry%3Dplt%26from%3Dmap%26fromPanelNum%3D1%26additionalHeight%3D76%26timestamp%3D202611111305%26locale%3Dko%26svcName%3Dmap_pcv5&searchType=place&lng=127.1234931&lat=37.1821079&c=15.00,0,0,0,dh" target="_blank" class="px-5 py-2 rounded-xl bg-crimson text-white font-bold text-xs hover:bg-crimsonHover transition">상담예약</a>
                <a href="https://www.instagram.com/mokdong_taekwondo?exln=MjlueWVtZGY3YXVk" target="_blank" class="px-5 py-2 rounded-xl bg-zinc-800 text-white font-bold text-xs hover:bg-zinc-700 transition">인스타그램 DM 상담</a>
            </div>
            <p class="pt-4">&copy; 2026 KDT APEX. ALL RIGHTS RESERVED.</p>
        </div>
    </footer>

    <!-- Script for FAQ accordion & mobile menu -->
    <script>
        function toggleFaq(id) {
            const content = document.getElementById(`faq-content-${id}`);
            const icon = document.getElementById(`faq-icon-${id}`);
            content.classList.toggle('hidden');
            icon.classList.toggle('rotate-180');
        }

        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        if(mobileMenuBtn && mobileMenu) {
            mobileMenuBtn.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });
        }
    </script>
</body>
</html>
