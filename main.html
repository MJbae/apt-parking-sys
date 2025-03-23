<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>아파트 주차 관리 시스템</title>
    <style>
        :root {
            --primary-color: #4a6da7;
            --primary-light: #e6eef8;
            --secondary-color: #f5a742;
            --success-color: #2ecc71;
            --danger-color: #e74c3c;
            --text-color: #333;
            --text-light: #666;
            --background: #f5f5f5;
            --border-color: #ddd;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', 'Malgun Gothic', sans-serif;
        }

        body {
            background-color: var(--background);
            color: var(--text-color);
            line-height: 1.8;
            padding: 20px;
            font-size: 18px;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        /* 로그인 페이지 스타일 */
        .login-container {
            max-width: 600px;
            margin: 50px auto;
            background: white;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .login-form {
            display: flex;
            flex-direction: column;
            gap: 25px;
            margin-top: 30px;
        }

        .login-input {
            padding: 15px;
            border: 2px solid var(--border-color);
            border-radius: 8px;
            font-size: 22px;
            width: 100%;
        }

        .login-button {
            padding: 15px;
            background-color: var(--primary-color);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 22px;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .login-button:hover {
            background-color: #3a5a85;
        }

        header {
            margin-bottom: 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }

        h1 {
            color: var(--primary-color);
            margin-bottom: 20px;
            font-size: 36px;
        }

        h2 {
            color: var(--primary-color);
            margin-bottom: 20px;
            font-size: 28px;
        }

        h3 {
            color: var(--primary-color);
            margin-bottom: 15px;
            font-size: 24px;
        }

        p {
            font-size: 20px;
            margin-bottom: 20px;
        }

        .user-controls {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        select, input, button {
            padding: 12px 18px;
            border: 2px solid var(--border-color);
            border-radius: 8px;
            font-size: 20px;
        }

        select {
            background-color: white;
            cursor: pointer;
        }

        button {
            background-color: var(--primary-color);
            color: white;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s;
            font-weight: bold;
            min-width: 100px;
        }

        button:hover {
            background-color: #3a5a85;
        }

        button.secondary {
            background-color: var(--success-color);
        }

        button.secondary:hover {
            background-color: #27ae60;
        }

        button.danger {
            background-color: var(--danger-color);
        }

        button.danger:hover {
            background-color: #c0392b;
        }

        .form-group {
            margin-bottom: 25px;
        }

        label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
            font-size: 22px;
        }

        .tabs {
            display: flex;
            margin-bottom: 30px;
            border-bottom: 2px solid var(--border-color);
        }

        .tab {
            padding: 15px 25px;
            cursor: pointer;
            border-bottom: 4px solid transparent;
            font-size: 22px;
            font-weight: bold;
        }

        .tab.active {
            border-bottom: 4px solid var(--primary-color);
            color: var(--primary-color);
        }

        .tab-content {
            display: none;
        }

        .tab-content.active {
            display: block;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 30px;
            font-size: 20px;
        }

        th, td {
            padding: 15px 20px;
            border-bottom: 2px solid var(--border-color);
            text-align: left;
        }

        th {
            background-color: var(--primary-light);
            font-weight: bold;
            font-size: 22px;
        }

        tr:hover {
            background-color: rgba(0, 0, 0, 0.03);
        }

        .badge {
            display: inline-block;
            padding: 8px 15px;
            border-radius: 6px;
            font-size: 18px;
            font-weight: bold;
            color: white;
            margin-right: 10px;
        }

        .badge.available {
            background-color: var(--success-color);
        }

        .badge.unavailable {
            background-color: var(--danger-color);
        }

        .alert {
            padding: 20px;
            margin-bottom: 30px;
            border-radius: 8px;
            display: none;
            font-size: 20px;
            font-weight: bold;
        }

        .alert.success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }

        .alert.error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }

        .action-buttons {
            display: flex;
            gap: 10px;
        }

        .detail-button {
            background-color: var(--secondary-color);
            color: white;
            border: none;
            padding: 8px 15px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            font-size: 18px;
        }

        .detail-button:hover {
            background-color: #d98e2d;
        }

        .empty-state {
            text-align: center;
            padding: 50px 0;
            color: var(--text-light);
            font-size: 22px;
        }

        /* 시간 선택기 스타일 */
        .time-selector {
            display: flex;
            gap: 15px;
            align-items: center;
            margin-top: 10px;
        }

        .time-selector select {
            padding: 12px;
            font-size: 20px;
            border: 2px solid var(--border-color);
            border-radius: 8px;
            background-color: white;
        }

        /* 모달 스타일 */
        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
        }

        .modal-content {
            background-color: white;
            margin: 10% auto;
            padding: 30px;
            border-radius: 10px;
            width: 80%;
            max-width: 600px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }

        .close-modal {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
        }

        .close-modal:hover {
            color: black;
        }

        .modal-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        /* 모바일 대응 */
        @media (max-width: 768px) {
            body {
                padding: 10px;
                font-size: 16px;
            }

            .container, .login-container {
                padding: 15px;
            }

            h1 {
                font-size: 28px;
            }

            h2 {
                font-size: 24px;
            }

            h3 {
                font-size: 20px;
            }

            .login-form {
                gap: 15px;
            }

            .login-input, .login-button {
                padding: 12px;
                font-size: 18px;
            }

            .tabs {
                flex-direction: column;
                border-bottom: none;
            }
            
            .tab {
                border-bottom: 1px solid var(--border-color);
                font-size: 20px;
                padding: 12px;
            }
            
            .tab.active {
                border-bottom: 1px solid var(--primary-color);
                background-color: var(--primary-light);
            }
            
            .user-controls {
                margin-top: 15px;
                width: 100%;
                justify-content: center;
                flex-direction: column;
            }

            select, input, button {
                font-size: 18px;
                padding: 10px 15px;
                width: 100%;
            }
            
            th, td {
                padding: 10px;
                font-size: 16px;
            }

            table {
                font-size: 16px;
            }

            .time-selector {
                flex-direction: column;
                align-items: flex-start;
            }

            .time-selector select {
                width: 100%;
            }

            .modal-content {
                width: 95%;
                margin: 5% auto;
                padding: 20px;
            }

            .modal-buttons {
                flex-direction: column;
                gap: 10px;
            }
        }
    </style>
</head>
<body>
    <!-- 로그인 페이지 -->
    <div id="login-page" class="login-container">
        <h1>아파트 주차 관리 시스템</h1>
        <p>세대를 선택하고 비밀번호를 입력하여 로그인해주세요.</p>
        
        <div class="alert error" id="login-error"></div>
        
        <form class="login-form" id="login-form">
            <select id="login-user-select" class="login-input">
                <option value="">세대 선택</option>
                <option value="101">101호</option>
                <option value="102">102호</option>
                <option value="201">201호</option>
                <option value="202">202호</option>
                <option value="301">301호</option>
                <option value="302">302호</option>
                <option value="401">401호</option>
                <option value="402">402호</option>
                <option value="501">501호</option>
                <option value="502">502호</option>
                <option value="601">601호</option>
                <option value="602">602호</option>
                <option value="701">701호</option>
                <option value="702">702호</option>
            </select>
            
            <input type="password" id="login-password" class="login-input" placeholder="비밀번호 입력 (초기 비밀번호: 0000)" maxlength="4" inputmode="numeric" pattern="[0-9]*">
            
            <button type="submit" class="login-button">로그인</button>
        </form>
    </div>

    <!-- 메인 콘텐츠 -->
    <div id="main-content" class="container" style="display: none;">
        <header>
            <h1>아파트 주차 관리 시스템</h1>
            <div class="user-controls">
                <p id="user-info" style="margin: 0;"></p>
                <button id="logout-btn">로그아웃</button>
            </div>
        </header>

        <div class="alert success" id="success-alert"></div>
        <div class="alert error" id="error-alert"></div>

        <div class="tabs">
            <div class="tab active" data-tab="availability">주차 현황</div>
            <div class="tab" data-tab="register">부재 등록</div>
            <div class="tab" data-tab="my-registrations">내 등록 관리</div>
        </div>

        <div class="tab-content active" id="availability-tab">
            <h2>주차 가능 현황</h2>
            <p>현재 및 향후 주차 가능한 자리를 확인하고 예약할 수 있습니다.</p>
            
            <table id="availability-table">
                <thead>
                    <tr>
                        <th>세대</th>
                        <th>부재 시작</th>
                        <th>부재 종료</th>
                        <th>상태</th>
                        <th>관리</th>
                    </tr>
                </thead>
                <tbody>
                    <!-- JavaScript로 채워질 부분 -->
                </tbody>
            </table>
            <div id="availability-empty" class="empty-state">
                <p>현재 등록된 주차 부재 정보가 없습니다.</p>
            </div>
        </div>

        <div class="tab-content" id="register-tab">
            <h2>주차 부재 등록</h2>
            <p>귀하의 차량이 자리를 비우는 시간을 등록하여 다른 주민들이 방문객을 위해 사용할 수 있도록 해주세요.</p>
            
            <form id="absence-form">
                <div class="form-group">
                    <label for="start-date">부재 시작 날짜</label>
                    <input type="date" id="start-date" required>
                    
                    <div class="time-selector">
                        <select id="start-hour">
                            <option value="">시간 선택</option>
                            <option value="AM-1">오전 1시</option>
                            <option value="AM-2">오전 2시</option>
                            <option value="AM-3">오전 3시</option>
                            <option value="AM-4">오전 4시</option>
                            <option value="AM-5">오전 5시</option>
                            <option value="AM-6">오전 6시</option>
                            <option value="AM-7">오전 7시</option>
                            <option value="AM-8">오전 8시</option>
                            <option value="AM-9">오전 9시</option>
                            <option value="AM-10">오전 10시</option>
                            <option value="AM-11">오전 11시</option>
                            <option value="AM-12">오전 12시</option>
                            <option value="PM-1">오후 1시</option>
                            <option value="PM-2">오후 2시</option>
                            <option value="PM-3">오후 3시</option>
                            <option value="PM-4">오후 4시</option>
                            <option value="PM-5">오후 5시</option>
                            <option value="PM-6">오후 6시</option>
                            <option value="PM-7">오후 7시</option>
                            <option value="PM-8">오후 8시</option>
                            <option value="PM-9">오후 9시</option>
                            <option value="PM-10">오후 10시</option>
                            <option value="PM-11">오후 11시</option>
                            <option value="PM-12">오후 12시</option>
                        </select>
                    </div>
                </div>
                
                <div class="form-group">
                    <label for="end-date">부재 종료 날짜</label>
                    <input type="date" id="end-date" required>
                    
                    <div class="time-selector">
                        <select id="end-hour">
                            <option value="">시간 선택</option>
                            <option value="AM-1">오전 1시</option>
                            <option value="AM-2">오전 2시</option>
                            <option value="AM-3">오전 3시</option>
                            <option value="AM-4">오전 4시</option>
                            <option value="AM-5">오전 5시</option>
                            <option value="AM-6">오전 6시</option>
                            <option value="AM-7">오전 7시</option>
                            <option value="AM-8">오전 8시</option>
                            <option value="AM-9">오전 9시</option>
                            <option value="AM-10">오전 10시</option>
                            <option value="AM-11">오전 11시</option>
                            <option value="AM-12">오전 12시</option>
                            <option value="PM-1">오후 1시</option>
                            <option value="PM-2">오후 2시</option>
                            <option value="PM-3">오후 3시</option>
                            <option value="PM-4">오후 4시</option>
                            <option value="PM-5">오후 5시</option>
                            <option value="PM-6">오후 6시</option>
                            <option value="PM-7">오후 7시</option>
                            <option value="PM-8">오후 8시</option>
                            <option value="PM-9">오후 9시</option>
                            <option value="PM-10">오후 10시</option>
                            <option value="PM-11">오후 11시</option>
                            <option value="PM-12">오후 12시</option>
                        </select>
                    </div>
                </div>
                
                <button type="submit">등록하기</button>
            </form>
        </div>

        <div class="tab-content" id="my-registrations-tab">
            <h2>내 등록 관리</h2>
            <p>귀하가 등록한 주차 부재 및 예약한 주차 공간을 관리합니다.</p>
            
            <h3>내가 등록한 부재</h3>
            <table id="my-absences-table">
                <thead>
                    <tr>
                        <th>부재 시작</th>
                        <th>부재 종료</th>
                        <th>상태</th>
                        <th>관리</th>
                    </tr>
                </thead>
                <tbody>
                    <!-- JavaScript로 채워질 부분 -->
                </tbody>
            </table>
            <div id="my-absences-empty" class="empty-state">
                <p>등록한 부재 정보가 없습니다.</p>
            </div>
            
            <h3>내가 예약한 주차 공간</h3>
            <table id="my-claims-table">
                <thead>
                    <tr>
                        <th>세대</th>
                        <th>시작 일시</th>
                        <th>종료 일시</th>
                        <th>관리</th>
                    </tr>
                </thead>
                <tbody>
                    <!-- JavaScript로 채워질 부분 -->
                </tbody>
            </table>
            <div id="my-claims-empty" class="empty-state">
                <p>예약한 주차 공간이 없습니다.</p>
            </div>
        </div>
    </div>

    <!-- 예약 모달 -->
    <div id="reservation-modal" class="modal">
        <div class="modal-content">
            <span class="close-modal">&times;</span>
            <h2>주차 공간 예약</h2>
            <p id="modal-description"></p>
            <div class="modal-buttons">
                <button id="confirm-reservation" class="secondary">예약하기</button>
                <button id="cancel-modal" class="danger">취소</button>
            </div>
        </div>
    </div>

    <script>
        // 데이터 모델
        let currentUser = null;
        let selectedAbsenceId = null;
        
        // 비밀번호 관리
        const getDefaultPasswords = () => {
            const savedPasswords = localStorage.getItem('parkingPasswords');
            if (savedPasswords) {
                try {
                    return JSON.parse(savedPasswords);
                } catch (e) {
                    console.error("비밀번호 파싱 오류:", e);
                    // 오류 발생 시 초기 비밀번호로 재설정
                    localStorage.removeItem('parkingPasswords');
                }
            }
            
            // 초기 비밀번호 설정 (모든 세대 "0000")
            const defaultPasswords = {};
            ["101", "102", "201", "202", "301", "302", "401", "402", "501", "502", "601", "602", "701", "702"].forEach(unit => {
                defaultPasswords[unit] = "0000";
            });
            
            localStorage.setItem('parkingPasswords', JSON.stringify(defaultPasswords));
            return defaultPasswords;
        };
        
        // 페이지 로드 시 로컬 스토리지에서 데이터 불러오기
        const loadData = () => {
            const absencesData = localStorage.getItem('parkingAbsences');
            return absencesData ? JSON.parse(absencesData) : [];
        };

        // 데이터 저장
        const saveData = (absences) => {
            localStorage.setItem('parkingAbsences', JSON.stringify(absences));
        };

        // 세션 상태 관리
        const loadSession = () => {
            const sessionUser = localStorage.getItem('parkingCurrentUser');
            return sessionUser ? sessionUser : null;
        };

        const saveSession = (user) => {
            if (user) {
                localStorage.setItem('parkingCurrentUser', user);
            } else {
                localStorage.removeItem('parkingCurrentUser');
            }
        };

        // 시간 선택기에서 날짜 객체 생성
        const createDateFromInputs = (dateInput, timeSelect) => {
            if (!dateInput || !timeSelect) return null;
            
            const date = new Date(dateInput);
            if (isNaN(date.getTime())) return null;
            
            const timeValue = timeSelect.split('-');
            if (timeValue.length !== 2) return null;
            
            const period = timeValue[0]; // AM or PM
            let hour = parseInt(timeValue[1]);
            
            // 시간 계산 (12시간제 -> 24시간제)
            if (period === 'PM' && hour < 12) {
                hour += 12;
            } else if (period === 'AM' && hour === 12) {
                hour = 0;
            }
            
            date.setHours(hour, 0, 0, 0);
            return date;
        };

        // 날짜 포맷팅 함수 - 개선됨
        const formatDate = (dateString) => {
            const date = new Date(dateString);
            const options = {
                year: 'numeric',
                month: '2-digit',
                day: '2-digit',
                hour: '2-digit',
                hour12: true
            };
            
            return date.toLocaleString('ko-KR', options).replace(/:\d{2}\s/, ' ');
        };

        // 초기화 함수
        const init = () => {
            // 비밀번호 초기화 - 확실하게 초기 비밀번호 설정
            const passwords = getDefaultPasswords();
            console.log("비밀번호 초기화 완료:", Object.keys(passwords).length, "개 세대");
            
            // 세션 로드
            currentUser = loadSession();
            console.log("세션 확인:", currentUser ? `${currentUser}호 로그인됨` : "로그인 안됨");
            
            if (currentUser) {
                try {
                    document.getElementById('login-page').style.display = 'none';
                    document.getElementById('main-content').style.display = 'block';
                    document.getElementById('user-info').textContent = `${currentUser}호 로그인 중`;
                    
                    // 데이터 로드 및 UI 업데이트
                    updateUI();
                } catch (e) {
                    console.error("로그인 상태 처리 중 오류:", e);
                    // 오류 발생 시 세션 초기화 후 다시 로그인하도록 함
                    currentUser = null;
                    saveSession(null);
                    document.getElementById('login-page').style.display = 'block';
                    document.getElementById('main-content').style.display = 'none';
                    showLoginError("오류가 발생했습니다. 다시 로그인해주세요.");
                }
            } else {
                document.getElementById('login-page').style.display = 'block';
                document.getElementById('main-content').style.display = 'none';
            }
            
            // 로그인 폼 이벤트 리스너
            document.getElementById('login-form').addEventListener('submit', (e) => {
                e.preventDefault();
                login();
            });
            
            // 엔터키로 로그인 가능하도록 추가
            document.getElementById('login-password').addEventListener('keypress', (e) => {
                if (e.key === 'Enter') {
                    e.preventDefault();
                    login();
                }
            });
            
            // 로그아웃 이벤트 리스너
            document.getElementById('logout-btn').addEventListener('click', () => {
                logout();
            });
            
            // 탭 전환 이벤트 리스너
            document.querySelectorAll('.tab').forEach(tab => {
                tab.addEventListener('click', () => {
                    document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
                    tab.classList.add('active');
                    
                    document.querySelectorAll('.tab-content').forEach(content => {
                        content.classList.remove('active');
                    });
                    
                    document.getElementById(`${tab.dataset.tab}-tab`).classList.add('active');
                });
            });
            
            // 부재 등록 폼 제출 이벤트 리스너
            document.getElementById('absence-form').addEventListener('submit', (e) => {
                e.preventDefault();
                registerAbsence();
            });
            
            // 예약 모달 이벤트 리스너
            document.querySelector('.close-modal').addEventListener('click', () => {
                closeModal();
            });
            
            document.getElementById('cancel-modal').addEventListener('click', () => {
                closeModal();
            });
            
            document.getElementById('confirm-reservation').addEventListener('click', () => {
                if (selectedAbsenceId) {
                    claimParking(selectedAbsenceId);
                    closeModal();
                }
            });
            
            // 모달 외부 클릭 시 닫기
            window.addEventListener('click', (e) => {
                if (e.target === document.getElementById('reservation-modal')) {
                    closeModal();
                }
            });
        };

        // 로그인 기능
        const login = () => {
            const selectedUser = document.getElementById('login-user-select').value;
            const password = document.getElementById('login-password').value;
            
            if (!selectedUser) {
                showLoginError('세대를 선택해주세요.');
                return;
            }
            
            if (!password) {
                showLoginError('비밀번호를 입력해주세요.');
                return;
            }
            
            // 비밀번호 확인
            const passwords = getDefaultPasswords();
            
            // 디버깅 메시지 (실제 비밀번호는 숨김)
            console.log("로그인 시도:", selectedUser, "입력된 비밀번호 길이:", password.length);
            
            if (passwords[selectedUser] !== password) {
                console.log("비밀번호 불일치: 예상값 길이 =", passwords[selectedUser].length, "입력값 길이 =", password.length);
                showLoginError('비밀번호가 일치하지 않습니다. 초기 비밀번호는 0000입니다.');
                return;
            }
            
            try {
                // 로그인 성공
                currentUser = selectedUser;
                saveSession(currentUser);
                
                document.getElementById('login-page').style.display = 'none';
                document.getElementById('main-content').style.display = 'block';
                document.getElementById('user-info').textContent = `${currentUser}호 로그인 중`;
                
                // 폼 초기화
                document.getElementById('login-form').reset();
                
                // 데이터 로드 및 UI 업데이트
                updateUI();
                
                console.log("로그인 성공:", currentUser);
            } catch (e) {
                console.error("로그인 처리 중 오류:", e);
                showLoginError('로그인 처리 중 오류가 발생했습니다. 다시 시도해주세요.');
            }
        };

        // 로그인 오류 표시
        const showLoginError = (message) => {
            const alert = document.getElementById('login-error');
            alert.textContent = message;
            alert.style.display = 'block';
            
            // 오류 메시지에 포커스 주기 (스크린 리더 사용자를 위함)
            alert.setAttribute('tabindex', '-1');
            alert.focus();
            
            setTimeout(() => {
                alert.style.display = 'none';
            }, 5000);
            
            // 디버깅용 콘솔 로그
            console.log("로그인 오류:", message);
        };

        // 로그아웃 기능
        const logout = () => {
            currentUser = null;
            saveSession(null);
            
            document.getElementById('login-page').style.display = 'block';
            document.getElementById('main-content').style.display = 'none';
            
            // 폼 초기화
            document.getElementById('login-form').reset();
        };

        // 모달 표시
        const openModal = (absenceId) => {
            selectedAbsenceId = absenceId;
            
            // 부재 정보 가져오기
            const absences = loadData();
            const absence = absences.find(a => a.id === absenceId);
            
            if (absence) {
                document.getElementById('modal-description').textContent = 
                    `${absence.user}호의 주차 공간을 예약하시겠습니까?\n` +
                    `기간: ${formatDate(absence.startDate)} ~ ${formatDate(absence.endDate)}`;
                
                document.getElementById('reservation-modal').style.display = 'block';
            }
        };

        // 모달 닫기
        const closeModal = () => {
            document.getElementById('reservation-modal').style.display = 'none';
            selectedAbsenceId = null;
        };

        // UI 업데이트 함수
        const updateUI = () => {
            updateAvailabilityTable();
            updateMyAbsencesTable();
            updateMyClaimsTable();
            
            // 오늘 날짜 이후로만 선택 가능하도록 설정
            const today = new Date();
            today.setHours(0, 0, 0, 0);
            
            const year = today.getFullYear();
            const month = String(today.getMonth() + 1).padStart(2, '0');
            const day = String(today.getDate()).padStart(2, '0');
            
            const minDate = `${year}-${month}-${day}`;
            
            document.getElementById('start-date').min = minDate;
            document.getElementById('end-date').min = minDate;
        };

        // 알림 표시 함수
        const showAlert = (type, message) => {
            const alert = document.getElementById(`${type}-alert`);
            alert.textContent = message;
            alert.style.display = 'block';
            
            setTimeout(() => {
                alert.style.display = 'none';
            }, 5000); // 노인 사용자를 위해 표시 시간 연장
        };

        // 주차 부재 등록 함수
        const registerAbsence = () => {
            if (!currentUser) {
                showAlert('error', '로그인이 필요합니다.');
                return;
            }
            
            const startDate = document.getElementById('start-date').value;
            const endDate = document.getElementById('end-date').value;
            const startHour = document.getElementById('start-hour').value;
            const endHour = document.getElementById('end-hour').value;
            
            if (!startDate || !endDate) {
                showAlert('error', '시작 및 종료 날짜를 모두 입력해주세요.');
                return;
            }
            
            if (!startHour || !endHour) {
                showAlert('error', '시작 및 종료 시간을 모두 선택해주세요.');
                return;
            }
            
            // 날짜 객체 생성
            const start = createDateFromInputs(startDate, startHour);
            const end = createDateFromInputs(endDate, endHour);
            const now = new Date();
            
            if (!start || !end) {
                showAlert('error', '날짜 형식이 올바르지 않습니다.');
                return;
            }
            
            if (start < now) {
                showAlert('error', '시작 시간은 현재 이후여야 합니다.');
                return;
            }
            
            if (end <= start) {
                showAlert('error', '종료 시간은 시작 시간 이후여야 합니다.');
                return;
            }
            
            // 데이터 로드
            const absences = loadData();
            
            // 중복 검사
            const hasOverlap = absences.some(absence => {
                if (absence.user === currentUser) {
                    const absenceStart = new Date(absence.startDate);
                    const absenceEnd = new Date(absence.endDate);
                    
                    // 기존 부재와 겹치는지 확인
                    return (start <= absenceEnd && end >= absenceStart);
                }
                return false;
            });
            
            if (hasOverlap) {
                showAlert('error', '이미 등록된 부재 기간과 겹칩니다.');
                return;
            }
            
            // 새 부재 추가
            const newAbsence = {
                id: Date.now().toString(),
                user: currentUser,
                startDate: start.toISOString(),
                endDate: end.toISOString(),
                claimedBy: null
            };
            
            absences.push(newAbsence);
            saveData(absences);
            
            // UI 업데이트
            updateUI();
            
            // 폼 초기화
            document.getElementById('absence-form').reset();
            
            // 알림 표시
            showAlert('success', '주차 부재가 성공적으로 등록되었습니다.');
        };

        // 주차 예약 취소 함수
        const cancelClaim = (absenceId) => {
            if (!currentUser) {
                showAlert('error', '로그인이 필요합니다.');
                return;
            }
            
            // 데이터 로드
            const absences = loadData();
            
            // 해당 부재 찾기
            const absenceIndex = absences.findIndex(a => a.id === absenceId);
            
            if (absenceIndex === -1) {
                showAlert('error', '해당 부재 정보를 찾을 수 없습니다.');
                return;
            }
            
            const absence = absences[absenceIndex];
            
            // 권한 확인
            if (absence.claimedBy !== currentUser) {
                showAlert('error', '자신이 예약한 주차만 취소할 수 있습니다.');
                return;
            }
            
            // 예약 취소
            absence.claimedBy = null;
            absences[absenceIndex] = absence;
            saveData(absences);
            
            // UI 업데이트
            updateUI();
            
            // 알림 표시
            showAlert('success', '주차 예약이 취소되었습니다.');
        };

        // 주차 부재 취소 함수
        const cancelAbsence = (absenceId) => {
            if (!currentUser) {
                showAlert('error', '로그인이 필요합니다.');
                return;
            }
            
            // 데이터 로드
            const absences = loadData();
            
            // 해당 부재 찾기
            const absenceIndex = absences.findIndex(a => a.id === absenceId);
            
            if (absenceIndex === -1) {
                showAlert('error', '해당 부재 정보를 찾을 수 없습니다.');
                return;
            }
            
            const absence = absences[absenceIndex];
            
            // 권한 확인
            if (absence.user !== currentUser) {
                showAlert('error', '자신이 등록한 부재만 취소할 수 있습니다.');
                return;
            }
            
            // 예약 확인
            if (absence.claimedBy) {
                showAlert('error', '이미 다른 세대가 예약한 부재는 취소할 수 없습니다.');
                return;
            }
            
            // 시작 시간 확인
            const startDate = new Date(absence.startDate);
            const now = new Date();
            
            if (startDate <= now) {
                showAlert('error', '이미 시작된 부재는 취소할 수 없습니다.');
                return;
            }
            
            // 부재 삭제
            absences.splice(absenceIndex, 1);
            saveData(absences);
            
            // UI 업데이트
            updateUI();
            
            // 알림 표시
            showAlert('success', '주차 부재가 취소되었습니다.');
        };

        // 주차 예약 함수
        const claimParking = (absenceId) => {
            if (!currentUser) {
                showAlert('error', '로그인이 필요합니다.');
                return;
            }
            
            // 데이터 로드
            const absences = loadData();
            
            // 해당 부재 찾기
            const absenceIndex = absences.findIndex(a => a.id === absenceId);
            
            if (absenceIndex === -1) {
                showAlert('error', '해당 부재 정보를 찾을 수 없습니다.');
                return;
            }
            
            const absence = absences[absenceIndex];
            
            // 자신의 부재인지 확인
            if (absence.user === currentUser) {
                showAlert('error', '자신의 부재 자리는 예약할 수 없습니다.');
                return;
            }
            
            // 이미 예약된 자리인지 확인
            if (absence.claimedBy) {
                showAlert('error', '이미 다른 세대가 예약한 자리입니다.');
                return;
            }
            
            // 시간 확인
            const endDate = new Date(absence.endDate);
            const now = new Date();
            
            if (endDate <= now) {
                showAlert('error', '이미 종료된 부재는 예약할 수 없습니다.');
                return;
            }
            
            // 중복 예약 검사
            const hasOverlap = absences.some(a => {
                if (a.claimedBy === currentUser && a.id !== absenceId) {
                    const aStart = new Date(a.startDate);
                    const aEnd = new Date(a.endDate);
                    const absenceStart = new Date(absence.startDate);
                    const absenceEnd = new Date(absence.endDate);
                    
                    // 기존 예약과 겹치는지 확인
                    return (absenceStart <= aEnd && absenceEnd >= aStart);
                }
                return false;
            });
            
            if (hasOverlap) {
                showAlert('error', '이미 예약한 다른 주차 기간과 겹칩니다.');
                return;
            }
            
            // 예약 처리
            absence.claimedBy = currentUser;
            absences[absenceIndex] = absence;
            saveData(absences);
            
            // UI 업데이트
            updateUI();
            
            // 알림 표시
            showAlert('success', `${absence.user}호의 주차 자리가 성공적으로 예약되었습니다.`);
        };

        // 주차 현황 테이블 업데이트
        const updateAvailabilityTable = () => {
            const table = document.getElementById('availability-table');
            const tbody = table.querySelector('tbody');
            const emptyState = document.getElementById('availability-empty');
            
            // 데이터 로드
            const absences = loadData();
            
            // 날짜 기준으로 정렬
            absences.sort((a, b) => new Date(a.startDate) - new Date(b.startDate));
            
            // 현재 날짜
            const now = new Date();
            
            // 종료된 부재 필터링
            const activeAbsences = absences.filter(absence => new Date(absence.endDate) > now);
            
            if (activeAbsences.length === 0) {
                tbody.innerHTML = '';
                emptyState.style.display = 'block';
                table.style.display = 'none';
                return;
            }
            
            emptyState.style.display = 'none';
            table.style.display = 'table';
            
            // 테이블 내용 생성
            tbody.innerHTML = '';
            
            activeAbsences.forEach(absence => {
                const row = document.createElement('tr');
                
                const startDate = new Date(absence.startDate);
                const endDate = new Date(absence.endDate);
                const isPast = startDate < now;
                
                // 상태 배지만 표시
                let statusBadge = '';
                
                if (absence.claimedBy) {
                    // 예약완료 - 빨간색
                    statusBadge = `<span class="badge unavailable">예약완료</span>`;
                } else {
                    // 예약하기 - 초록색
                    statusBadge = `<span class="badge available">예약하기</span>`;
                }

                // 상세 버튼 - 예약하기 기능
                let detailButton = '';
                if (!absence.claimedBy && absence.user !== currentUser && !isPast) {
                    detailButton = `<button class="detail-button" onclick="openModal('${absence.id}')">예약하기</button>`;
                } else {
                    detailButton = '-';
                }
                
                row.innerHTML = `
                    <td>${absence.user}호</td>
                    <td>${formatDate(absence.startDate)}</td>
                    <td>${formatDate(absence.endDate)}</td>
                    <td>${statusBadge}</td>
                    <td>${detailButton}</td>
                `;
                
                tbody.appendChild(row);
            });
        };

        // 내 부재 테이블 업데이트
        const updateMyAbsencesTable = () => {
            if (!currentUser) return;
            
            const table = document.getElementById('my-absences-table');
            const tbody = table.querySelector('tbody');
            const emptyState = document.getElementById('my-absences-empty');
            
            // 데이터 로드
            const absences = loadData();
            
            // 내 부재만 필터링
            const myAbsences = absences.filter(absence => absence.user === currentUser);
            
            // 날짜 기준으로 정렬
            myAbsences.sort((a, b) => new Date(a.startDate) - new Date(b.startDate));
            
            if (myAbsences.length === 0) {
                tbody.innerHTML = '';
                emptyState.style.display = 'block';
                table.style.display = 'none';
                return;
            }
            
            emptyState.style.display = 'none';
            table.style.display = 'table';
            
            // 현재 날짜
            const now = new Date();
            
            // 테이블 내용 생성
            tbody.innerHTML = '';
            
            myAbsences.forEach(absence => {
                const row = document.createElement('tr');
                
                const startDate = new Date(absence.startDate);
                const endDate = new Date(absence.endDate);
                const isPast = startDate < now;
                const isEnded = endDate < now;
                
                let statusBadge = '';
                let actionButton = '';
                
                if (isEnded) {
                    statusBadge = `<span class="badge unavailable">종료됨</span>`;
                    actionButton = '-';
                } else if (absence.claimedBy) {
                    statusBadge = `<span class="badge unavailable">예약됨</span> (${absence.claimedBy}호)`;
                    actionButton = '-';
                } else if (isPast) {
                    statusBadge = `<span class="badge unavailable">진행 중</span>`;
                    actionButton = '-';
                } else {
                    statusBadge = `<span class="badge available">예약 가능</span>`;
                    actionButton = `<button class="danger" onclick="cancelAbsence('${absence.id}')">취소</button>`;
                }
                
                row.innerHTML = `
                    <td>${formatDate(absence.startDate)}</td>
                    <td>${formatDate(absence.endDate)}</td>
                    <td>${statusBadge}</td>
                    <td>${actionButton}</td>
                `;
                
                tbody.appendChild(row);
            });
        };

        // 내 예약 테이블 업데이트
        const updateMyClaimsTable = () => {
            if (!currentUser) return;
            
            const table = document.getElementById('my-claims-table');
            const tbody = table.querySelector('tbody');
            const emptyState = document.getElementById('my-claims-empty');
            
            // 데이터 로드
            const absences = loadData();
            
            // 내 예약만 필터링
            const myClaims = absences.filter(absence => absence.claimedBy === currentUser);
            
            // 날짜 기준으로 정렬
            myClaims.sort((a, b) => new Date(a.startDate) - new Date(b.startDate));
            
            if (myClaims.length === 0) {
                tbody.innerHTML = '';
                emptyState.style.display = 'block';
                table.style.display = 'none';
                return;
            }
            
            emptyState.style.display = 'none';
            table.style.display = 'table';
            
            // 현재 날짜
            const now = new Date();
            
            // 테이블 내용 생성
            tbody.innerHTML = '';
            
            myClaims.forEach(claim => {
                const row = document.createElement('tr');
                
                const endDate = new Date(claim.endDate);
                const isActive = endDate > now;
                
                row.innerHTML = `
                    <td>${claim.user}호</td>
                    <td>${formatDate(claim.startDate)}</td>
                    <td>${formatDate(claim.endDate)}</td>
                    <td>${isActive ? 
                        `<button class="danger" onclick="cancelClaim('${claim.id}')">취소</button>` : '-'}
                    </td>
                `;
                
                tbody.appendChild(row);
            });
        };

        // 페이지 로드 시 초기화
        document.addEventListener('DOMContentLoaded', () => {
            try {
                init();
                console.log("시스템 초기화 완료");
            } catch (e) {
                console.error("시스템 초기화 중 오류:", e);
                alert("시스템 초기화 중 오류가 발생했습니다. 페이지를 새로고침해주세요.");
            }
        });

        // 모달 열기 함수를 전역으로 노출
        window.openModal = openModal;
        window.cancelClaim = cancelClaim;
        window.cancelAbsence = cancelAbsence;
    </script>
</body>
</html>
