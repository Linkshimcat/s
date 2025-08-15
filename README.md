[LINK AI.html](https://github.com/user-attachments/files/21795235/LINK.AI.html)<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LINK AI 클론</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;900&family=Noto+Sans+KR:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        /* 사용자 정의 스타일 */
        body {
            font-family: 'Noto Sans KR', 'Inter', sans-serif;
            background-color: #000000;
            color: #ffffff;
            overflow-x: hidden;
        }
        /* 텍스트 그라데이션 효과 */
        .text-gradient {
            background: linear-gradient(90deg, #6FFF50, #50C8FF);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-fill-color: transparent;
        }
        /* 커스텀 그림자 효과 */
        .glow-shadow-purple {
            box-shadow: 0 0 15px rgba(173, 113, 255, 0.4), 0 0 30px rgba(173, 113, 255, 0.3);
        }
        .glow-shadow-green {
            box-shadow: 0 0 15px rgba(111, 255, 80, 0.4), 0 0 30px rgba(111, 255, 80, 0.3);
        }
        /* 섹션 간 구분선 */
        .section-divider {
            height: 10vh;
        }
        /* 애니메이션을 위한 클래스 */
        .fade-in-up {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        .fade-in-up.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="bg-black text-white">

    <!-- 전체 컨테이너 -->
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 max-w-4xl">

        <!-- 최상단 헤더 섹션 -->
        <header class="text-center py-20 sm:py-32 fade-in-up">
            <h1 class="text-4xl sm:text-5xl md:text-6xl font-black leading-tight">
                이제부터, <br class="sm:hidden">
                <span class="text-gradient font-black tracking-tighter">LINK AI</span>
                <br>이용해보세요!
            </h1>
            <div class="mt-8">
                <button class="w-full max-w-sm bg-gradient-to-r from-purple-600 to-blue-500 text-white font-bold py-4 px-6 rounded-2xl text-lg flex items-center justify-between mx-auto glow-shadow-purple hover:scale-105 transition-transform duration-300">
                    <span>지금 바로 시작하기</span>
                    <span class="text-2xl">🐱</span>
                </button>
            </div>
        </header>

        <div class="section-divider"></div>

        <!-- 기능 소개 섹션 -->
        <section class="text-center fade-in-up">
            <h2 class="text-4xl font-black tracking-tighter text-gradient">LINK AI</h2>
            <p class="mt-4 text-xl sm:text-2xl text-gray-300">
                추론 🤔, 심층, 검색 🔎, 창작 🐱, 캔버스, 등등..
            </p>
            <div class="mt-8">
                <button class="bg-gray-800 text-white font-bold py-3 px-8 rounded-full text-lg hover:bg-gray-700 transition-colors duration-300">
                    <span>더 기능하나</span>
                    <span class="ml-2">👌</span>
                </button>
            </div>
        </section>

        <div class="section-divider"></div>

        <!-- 자동 요약 기능 섹션 -->
        <section class="text-center fade-in-up">
            <h2 class="text-3xl sm:text-4xl font-bold">
                아니, 요약이 <span class="text-green-400">Auto</span>를 해준다고??
            </h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 mt-10">
                <div class="bg-green-500/10 border border-green-500/30 p-6 rounded-2xl glow-shadow-green">
                    <h3 class="text-xl font-bold text-green-300">LIVE OVERVIEW</h3>
                </div>
                <div class="bg-purple-500/10 border border-purple-500/30 p-6 rounded-2xl">
                    <h3 class="text-xl font-bold">미팅 요약 📑</h3>
                </div>
                <div class="bg-gradient-to-r from-orange-500/80 to-red-500/80 p-6 rounded-2xl">
                    <h3 class="text-xl font-bold">내용 요약 ✨</h3>
                </div>
                <div class="bg-blue-500/10 border border-blue-500/30 p-6 rounded-2xl flex items-center justify-between">
                    <h3 class="text-xl font-bold">핸드오프 자동화</h3>
                    <span class="text-2xl">🤝</span>
                </div>
                <div class="bg-gradient-to-r from-purple-600/80 to-indigo-600/80 p-6 rounded-2xl flex items-center justify-between">
                    <h3 class="text-xl font-bold">업무 자동화</h3>
                    <span class="text-2xl">🤖</span>
                </div>
            </div>
        </section>

        <div class="section-divider"></div>

        <!-- AI Chat 섹션 -->
        <section class="fade-in-up">
            <div class="bg-gradient-to-br from-purple-600 via-black to-green-500 p-1 rounded-3xl">
                <div class="bg-black rounded-3xl p-6 sm:p-10">
                    <h2 class="text-3xl font-bold mb-6">AI Chat</h2>
                    <div class="space-y-4">
                        <div class="bg-gray-800 p-4 rounded-xl">
                            <p>안녕하세요, User님! 👋</p>
                        </div>
                        <div class="bg-gray-800 p-4 rounded-xl flex items-center">
                            <span class="mr-3 text-xl">🐱</span>
                            <p>프로젝트 요약본을 만들어주세요!</p>
                        </div>
                        <div class="bg-gray-800 p-4 rounded-xl flex items-center">
                            <span class="mr-3 text-xl">🐱</span>
                            <p>오늘의 할 일을 정리해주세요!</p>
                        </div>
                         <div class="bg-gray-800 p-4 rounded-xl flex items-center">
                            <span class="mr-3 text-xl">🐱</span>
                            <p>시작하기를 눌러주세요!</p>
                        </div>
                    </div>
                    <button class="mt-8 w-full bg-green-500 text-black font-bold py-4 rounded-2xl text-lg hover:bg-green-400 transition-colors duration-300">
                        시작하기
                    </button>
                </div>
            </div>
        </section>

        <div class="section-divider"></div>

        <!-- 스토어 섹션 -->
        <section class="flex flex-col md:flex-row items-center gap-8 fade-in-up">
            <div class="flex-1 text-center md:text-left">
                <h3 class="text-2xl font-bold">저희 스토어도</h3>
                <h2 class="text-4xl font-black text-gradient">LINKCAT STORE</h2>
                <button class="mt-6 bg-white text-black font-bold py-3 px-8 rounded-full text-lg hover:scale-105 transition-transform duration-300">
                    바로가기
                </button>
            </div>
            <div class="flex-1 w-full max-w-xs mx-auto">
                <!-- 스마트폰 목업 -->
                <div class="bg-black border-8 border-gray-800 rounded-[40px] shadow-2xl overflow-hidden" style="height: 600px;">
                    <div class="bg-gradient-to-b from-[#2c0a4a] to-[#1a0a2e] w-full h-full p-4 flex flex-col text-white">
                        <!-- 상단 바 -->
                        <div class="flex justify-between items-center px-2">
                            <span class="text-sm font-semibold">3:12</span>
                            <div class="w-24 h-6 bg-black rounded-full"></div>
                            <div class="flex items-center space-x-1">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.111 16.556A5.5 5.5 0 0112 15a5.5 5.5 0 013.889 1.556M12 21a9 9 0 100-18 9 9 0 000 18z" /></svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" /><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z" /></svg>
                            </div>
                        </div>
                        
                        <!-- 헤더 -->
                        <div class="flex justify-between items-center mt-4 px-2">
                            <h1 class="text-xl font-bold tracking-wider">
                                <span class="text-purple-400">↩</span>LINKCAT
                            </h1>
                            <div class="flex items-center space-x-4">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" /></svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" /></svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" /></svg>
                            </div>
                        </div>

                        <!-- 메인 컨텐츠 -->
                        <div class="flex-grow mt-6 overflow-y-auto">
                            <h2 class="text-3xl font-black text-purple-300 px-2">LINKCAT'S POP UP # SHOP</h2>
                            
                            <!-- 상품 카드 -->
                            <div class="mt-4 space-y-4">
                                <div class="bg-black/30 rounded-2xl p-3">
                                    <div class="w-full h-40 bg-black rounded-lg flex items-center justify-center">
                                        <p class="text-gray-500 text-sm">Image Placeholder</p>
                                    </div>
                                    <div class="flex justify-between items-center mt-3">
                                        <div>
                                            <p class="font-bold">| WOOP HOODIE</p>
                                            <p class="text-sm text-gray-400">| 100$</p>
                                        </div>
                                        <button class="bg-gray-700 rounded-full p-2">
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" /></svg>
                                        </button>
                                    </div>
                                </div>
                                <div class="bg-black/30 rounded-2xl p-3">
                                    <div class="w-full h-40 bg-black rounded-lg flex items-center justify-center">
                                        <p class="text-gray-500 text-sm">Image Placeholder</p>
                                    </div>
                                    <div class="flex justify-between items-center mt-3">
                                        <div>
                                            <p class="font-bold">| WOOP HOODIE</p>
                                            <p class="text-sm text-gray-400">| 100$</p>
                                        </div>
                                        <button class="bg-gray-700 rounded-full p-2">
                                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" /></svg>
                                        </button>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- 하단 네비게이션 -->
                        <div class="mt-auto bg-black/50 rounded-full p-2 flex justify-around items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7 text-purple-400" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" /></svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" /></svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.246 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" /></svg>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <div class="section-divider"></div>

        <!-- 포트폴리오 섹션 -->
        <section class="text-center fade-in-up">
             <h2 class="text-3xl sm:text-4xl font-bold mb-8">
                <span class="text-gradient">LINKSHIMCAT</span> 포트폴리오 보러 올 사람?
            </h2>
            <div class="bg-gray-900 rounded-2xl p-4">
                <div class="aspect-w-16 aspect-h-9 bg-gradient-to-br from-purple-600 to-blue-500 rounded-lg flex items-center justify-center">
                     <div class="text-center">
                        <h3 class="text-2xl font-bold">Lunch & Learn Share</h3>
                        <p class="text-gray-300">Video Placeholder</p>
                    </div>
                </div>
            </div>
             <button class="mt-8 bg-gray-800 text-white font-bold py-3 px-8 rounded-full text-lg hover:bg-gray-700 transition-colors duration-300">
                About
            </button>
        </section>

        <!-- 푸터 -->
        <footer class="text-center py-20">
             <div class="inline-block p-4 border-2 border-gray-700 rounded-full cursor-pointer hover:bg-gray-800" onclick="scrollToTop()">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m18 15-6-6-6 6"/></svg>
            </div>
            <p class="mt-4 text-gray-500">© 2024 LINK AI Clone</p>
        </footer>

    </div>

    <script>
        // 스크롤 맨 위로 이동
        function scrollToTop() {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // 스크롤 시 요소 나타나는 애니메이션
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, {
            threshold: 0.1
        });

        document.querySelectorAll('.fade-in-up').forEach(el => {
            observer.observe(el);
        });
    </script>
</body>
</html>

