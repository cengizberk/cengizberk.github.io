<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vize Hesaplama 180/90 - Nikah Memuru Cengiz BERK</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --light-color: #ecf0f1;
            --dark-color: #34495e;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            background-color: white;
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }
        
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 2px solid var(--light-color);
        }
        
        .title-section {
            text-align: left;
        }
        
        .main-title {
            color: var(--primary-color);
            margin: 0;
            font-size: 2rem;
            font-weight: bold;
        }
        
        .subtitle {
            font-size: 1.2rem;
            color: var(--dark-color);
            margin-top: 5px;
            font-weight: normal;
        }
        
        .contact-info {
            text-align: right;
            color: var(--dark-color);
        }
        
        .contact-info .phone {
            font-weight: bold;
            font-size: 1.3rem;
            color: var(--secondary-color);
            margin-bottom: 5px;
        }
        
        .contact-info .email {
            font-size: 1rem;
            color: var(--dark-color);
        }
        
        h2 {
            color: var(--dark-color);
            margin-top: 25px;
            margin-bottom: 15px;
            font-size: 1.4rem;
        }
        
        .input-section {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-bottom: 20px;
        }
        
        @media (max-width: 768px) {
            .input-section {
                grid-template-columns: 1fr;
            }
            
            .header {
                flex-direction: column;
                text-align: center;
            }
            
            .contact-info {
                text-align: center;
                margin-top: 15px;
            }
        }
        
        .input-group {
            margin-bottom: 15px;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
            color: var(--dark-color);
        }
        
        input[type="date"] {
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 16px;
            width: 100%;
            box-sizing: border-box;
        }
        
        .travel-inputs {
            margin-bottom: 10px;
        }
        
        .travel-item {
            display: grid;
            grid-template-columns: 1fr 1fr auto;
            gap: 10px;
            margin-bottom: 15px;
            padding: 15px;
            background-color: #f8f9fa;
            border-radius: 4px;
            align-items: end;
            border-left: 4px solid var(--secondary-color);
        }
        
        button {
            background-color: var(--secondary-color);
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 14px;
            transition: background-color 0.3s;
            font-weight: bold;
        }
        
        button:hover {
            background-color: #2980b9;
        }
        
        .travel-history {
            margin-top: 20px;
            max-height: 400px;
            overflow-y: auto;
        }
        
        .travel-history-item {
            display: flex;
            justify-content: space-between;
            padding: 12px;
            background-color: #f8f9fa;
            margin-bottom: 8px;
            border-radius: 4px;
            border-left: 4px solid var(--secondary-color);
        }
        
        .travel-dates {
            font-weight: bold;
        }
        
        .travel-days {
            color: var(--accent-color);
            font-weight: bold;
            font-size: 1.1rem;
        }
        
        .summary {
            background-color: var(--light-color);
            padding: 15px;
            border-radius: 4px;
            margin-top: 20px;
        }
        
        .summary-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
        }
        
        .status-ok {
            color: #27ae60;
            font-weight: bold;
        }
        
        .status-warning {
            color: #f39c12;
            font-weight: bold;
        }
        
        .status-danger {
            color: var(--accent-color);
            font-weight: bold;
        }
        
        .controls {
            display: flex;
            gap: 10px;
            margin-top: 15px;
        }
        
        .btn-clear {
            background-color: #95a5a6;
        }
        
        .btn-clear:hover {
            background-color: #7f8c8d;
        }
        
        .days-display {
            margin-top: 8px;
            grid-column: 1 / -1;
        }
        
        .stay-duration {
            font-size: 1.3rem;
            font-weight: bold;
            padding: 10px 15px;
            border-radius: 4px;
            text-align: center;
            margin-top: 5px;
        }
        
        .stay-duration.confirmed {
            background-color: #e8f6f3;
            color: #27ae60;
            border: 2px solid #27ae60;
        }
        
        .info-box {
            background-color: #e8f4fd;
            border-left: 4px solid var(--secondary-color);
            padding: 15px;
            margin-bottom: 20px;
            border-radius: 4px;
        }
        
        .period-info {
            background-color: #e8f4fd;
            padding: 12px;
            border-radius: 4px;
            margin-top: 10px;
            text-align: center;
            font-weight: bold;
            font-size: 1.1rem;
        }
        
        .travel-input-group {
            margin-bottom: 5px;
        }
        
        .remaining-ok {
            color: #27ae60;
            background-color: #e8f6f3;
        }
        
        .remaining-warning {
            color: #f39c12;
            background-color: #fff8e1;
        }
        
        .remaining-danger {
            color: #e74c3c;
            background-color: #fdedec;
        }
        
        .future-stay {
            background-color: #e8f6f3;
            padding: 25px;
            border-radius: 10px;
            margin-top: 20px;
            text-align: center;
            border: 3px solid #27ae60;
        }
        
        .future-stay-title {
            font-size: 1.4rem;
            font-weight: bold;
            color: #2c3e50;
            margin-bottom: 15px;
        }
        
        .future-stay-date {
            font-size: 2.5rem;
            font-weight: bold;
            color: #27ae60;
            margin: 20px 0;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
        
        .future-stay-days {
            font-size: 1.3rem;
            color: #2c3e50;
            margin-bottom: 10px;
        }
        
        .remaining-days {
            font-size: 1.3rem;
            font-weight: bold;
            text-align: center;
            margin-top: 20px;
            padding: 15px;
            border-radius: 8px;
            background-color: #e8f4fd;
        }
        
        .calculation-explanation {
            font-size: 1rem;
            color: #7f8c8d;
            text-align: center;
            margin-top: 15px;
            font-style: italic;
            line-height: 1.4;
        }
        
        .highlight-date {
            font-size: 2.5rem;
            font-weight: bold;
            color: #27ae60;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="title-section">
                <div class="main-title">Vize Hesaplama 180/90</div>
                <div class="subtitle">Nikah Memuru Cengiz BERK</div>
            </div>
            <div class="contact-info">
                <div class="phone">0532 286 28 53</div>
                <div class="email">cengizberk@hotmail.com</div>
                <div>İletişim</div>
            </div>
        </div>
        
        <div class="info-box">
            <p>Bu araç, Schengen vizesi kurallarına göre 180 günlük süre içinde maksimum 90 gün kalış hakkınızı hesaplar. Son giriş-çıkış tarihlerinizi ekleyerek mevcut durumunuzu kontrol edebilirsiniz.</p>
        </div>
        
        <div class="input-section">
            <div>
                <h2>Hesaplama Tarih Aralığı</h2>
                <div class="period-info" id="periodInfo">
                    Son 180 günlük dönem: <span id="periodDates"></span>
                </div>
                
                <h2>Giriş-Çıkış Tarihleri</h2>
                <div id="travelInputs">
                    <!-- Giriş-çıkış tarih çiftleri buraya eklenecek -->
                </div>
                
                <button onclick="addTravelDate()">+ Yeni Giriş-Çıkış Ekle</button>
            </div>
            
            <div>
                <h2>Hesaplama Sonuçları</h2>
                <div class="summary" id="summary">
                    <!-- Özet bilgiler burada gösterilecek -->
                </div>
                
                <div id="lastStay">
                    <!-- Sonuç burada gösterilecek -->
                </div>
                
                <div class="travel-history" id="travelHistory">
                    <!-- Kaldığı tarihler burada gösterilecek -->
                </div>
            </div>
        </div>
        
        <div class="controls">
            <button onclick="calculatePeriods()">Hesapla</button>
            <button class="btn-clear" onclick="clearAll()">Temizle</button>
        </div>
    </div>

    <script>
        let travelCount = 0;
        const maxTravelEntries = 10;
        let periodStartDate, periodEndDate;
        
        // Sayfa yüklendiğinde varsayılan giriş-çıkış alanını ekle
        window.onload = function() {
            // 180 günlük dönemi hesapla
            calculatePeriodDates();
            
            // Dönem bilgisini güncelle
            updatePeriodInfo();
            
            // İlk giriş-çıkış alanını ekle
            addTravelDate();
            
            // Varsayılan hesaplamayı yap
            calculatePeriods();
        };
        
        // 180 günlük dönemi hesapla
        function calculatePeriodDates() {
            const today = new Date();
            periodEndDate = new Date(today);
            
            // 180 gün öncesini hesapla
            periodStartDate = new Date(today);
            periodStartDate.setDate(periodStartDate.getDate() - 179); // 180 günlük periyot
        }
        
        // Dönem bilgisini güncelle
        function updatePeriodInfo() {
            document.getElementById('periodDates').textContent = `${formatDate(periodStartDate)} - ${formatDate(periodEndDate)}`;
        }
        
        // Yeni giriş-çıkış tarih çifti ekle
        function addTravelDate() {
            if (travelCount >= maxTravelEntries) {
                alert(`Maksimum ${maxTravelEntries} giriş-çıkış çifti ekleyebilirsiniz.`);
                return;
            }
            
            const travelInputs = document.getElementById('travelInputs');
            const travelDiv = document.createElement('div');
            travelDiv.className = 'travel-item';
            travelDiv.id = `travel-${travelCount}`;
            
            travelDiv.innerHTML = `
                <div class="travel-input-group">
                    <label>Giriş Tarihi:</label>
                    <input type="date" id="entry-${travelCount}" class="entry-date" 
                           min="${periodStartDate.toISOString().split('T')[0]}" 
                           max="${periodEndDate.toISOString().split('T')[0]}"
                           onchange="updateDaysDisplay(${travelCount})">
                </div>
                <div class="travel-input-group">
                    <label>Çıkış Tarihi:</label>
                    <input type="date" id="exit-${travelCount}" class="exit-date" 
                           min="${periodStartDate.toISOString().split('T')[0]}" 
                           max="${periodEndDate.toISOString().split('T')[0]}"
                           onchange="updateDaysDisplay(${travelCount})">
                </div>
                <div>
                    <button onclick="removeTravelDate(${travelCount})">Sil</button>
                </div>
                <div class="days-display" id="days-display-${travelCount}">
                    <!-- Gün bilgisi burada gösterilecek -->
                </div>
            `;
            
            travelInputs.appendChild(travelDiv);
            travelCount++;
        }
        
        // Giriş-çıkış tarih çiftini sil
        function removeTravelDate(index) {
            const travelItem = document.getElementById(`travel-${index}`);
            if (travelItem) {
                travelItem.remove();
            }
        }
        
        // Gün bilgilerini güncelle
        function updateDaysDisplay(index) {
            const entryDateElem = document.getElementById(`entry-${index}`);
            const exitDateElem = document.getElementById(`exit-${index}`);
            const daysDisplayElem = document.getElementById(`days-display-${index}`);
            
            // Giriş tarihi kontrolü
            if (entryDateElem.value) {
                if (exitDateElem.value) {
                    const entryDate = new Date(entryDateElem.value);
                    const exitDate = new Date(exitDateElem.value);
                    const stayDays = Math.floor((exitDate - entryDate) / (1000 * 60 * 60 * 24)) + 1;
                    daysDisplayElem.innerHTML = `<div class="stay-duration confirmed">${stayDays} GÜN</div>`;
                } else {
                    daysDisplayElem.innerHTML = `<div class="stay-duration confirmed">Aktif Kalış</div>`;
                }
            } else {
                daysDisplayElem.innerHTML = '';
            }
        }
        
        // Tüm giriş-çıkış tarihlerini temizle
        function clearAll() {
            document.getElementById('travelInputs').innerHTML = '';
            document.getElementById('summary').innerHTML = '';
            document.getElementById('travelHistory').innerHTML = '';
            document.getElementById('lastStay').innerHTML = '';
            travelCount = 0;
            addTravelDate();
        }
        
        // 180 günlük dönemleri hesapla
        function calculatePeriods() {
            const summaryContainer = document.getElementById('summary');
            const travelHistoryContainer = document.getElementById('travelHistory');
            const lastStayContainer = document.getElementById('lastStay');
            
            summaryContainer.innerHTML = '';
            travelHistoryContainer.innerHTML = '';
            lastStayContainer.innerHTML = '';
            
            // Giriş-çıkış tarihlerini topla
            const travelHistory = getTravelHistory();
            
            // Hesaplama aralığındaki toplam günü hesapla
            const daysInPeriod = calculateDaysInPeriod(periodStartDate, periodEndDate, travelHistory);
            
            // Ülkede kalınabilecek son tarihi hesapla
            const maxStayInfo = calculateMaxStay(daysInPeriod);
            
            // Özet bilgileri göster
            showSummary(daysInPeriod);
            
            // Sonuçları göster
            showResults(maxStayInfo, daysInPeriod);
            
            // Kaldığı tarihleri göster
            showTravelHistory(travelHistory);
        }
        
        // Giriş-çıkış tarihlerini al
        function getTravelHistory() {
            const travelHistory = [];
            
            for (let i = 0; i < travelCount; i++) {
                const entryDateElem = document.getElementById(`entry-${i}`);
                const exitDateElem = document.getElementById(`exit-${i}`);
                
                if (entryDateElem && entryDateElem.value) {
                    const entryDate = new Date(entryDateElem.value);
                    let exitDate;
                    let days;
                    
                    if (exitDateElem && exitDateElem.value) {
                        exitDate = new Date(exitDateElem.value);
                        days = Math.floor((exitDate - entryDate) / (1000 * 60 * 60 * 24)) + 1;
                    } else {
                        // Çıkış tarihi boşsa, bugünü kullan
                        exitDate = new Date();
                        days = Math.floor((exitDate - entryDate) / (1000 * 60 * 60 * 24)) + 1;
                    }
                    
                    if (exitDate >= entryDate) {
                        travelHistory.push({
                            entry: entryDate,
                            exit: exitDate,
                            days: days,
                            hasExit: !!(exitDateElem && exitDateElem.value)
                        });
                    }
                }
            }
            
            // Tarihe göre sırala (en yeni en üstte)
            travelHistory.sort((a, b) => b.exit - a.exit);
            
            return travelHistory;
        }
        
        // Belirli bir dönemdeki toplam kalış gününü hesapla
        function calculateDaysInPeriod(periodStart, periodEnd, travelHistory) {
            let totalDays = 0;
            
            travelHistory.forEach(travel => {
                const entry = travel.entry;
                const exit = travel.exit;
                
                // Seyahatin dönemle kesişip kesişmediğini kontrol et
                if (entry <= periodEnd && exit >= periodStart) {
                    // Kesişen gün sayısını hesapla
                    const overlapStart = entry > periodStart ? entry : periodStart;
                    const overlapEnd = exit < periodEnd ? exit : periodEnd;
                    
                    const overlapDays = Math.floor((overlapEnd - overlapStart) / (1000 * 60 * 60 * 24)) + 1;
                    totalDays += overlapDays;
                }
            });
            
            return totalDays;
        }
        
        // Ülkede kalınabilecek maksimum tarihi hesapla
        function calculateMaxStay(daysInPeriod) {
            const remainingDays = 90 - daysInPeriod;
            const today = new Date();
            
            if (remainingDays <= 0) {
                return {
                    date: today,
                    days: 0,
                    isPossible: false,
                    message: "Kalan kalış hakkınız bulunmamaktadır"
                };
            }
            
            // Bugünden itibaren kalan gün kadar ileri tarih hesapla
            const maxStayDate = new Date(today);
            maxStayDate.setDate(maxStayDate.getDate() + remainingDays);
            
            // 180 günlük dönemin son tarihini geçemez
            if (maxStayDate > periodEndDate) {
                return {
                    date: periodEndDate,
                    days: Math.floor((periodEndDate - today) / (1000 * 60 * 60 * 24)) + 1,
                    isPossible: true,
                    message: `${formatDate(periodEndDate)} tarihine kadar kalabilirsiniz`,
                    calculation: `Bugün (${formatDate(today)}) + ${remainingDays} gün = <span class="highlight-date">${formatDate(maxStayDate)}</span> (180 gün sınırı nedeniyle ${formatDate(periodEndDate)})`
                };
            }
            
            return {
                date: maxStayDate,
                days: remainingDays,
                isPossible: true,
                message: `${formatDate(maxStayDate)} tarihine kadar kalabilirsiniz`,
                calculation: `Bugün (${formatDate(today)}) + ${remainingDays} gün = <span class="highlight-date">${formatDate(maxStayDate)}</span>`
            };
        }
        
        // Özet bilgileri göster
        function showSummary(daysInPeriod) {
            const summaryContainer = document.getElementById('summary');
            
            // Durum değerlendirmesi
            let status = '';
            let statusClass = '';
            
            if (daysInPeriod <= 90) {
                status = 'Kurallara Uygun';
                statusClass = 'status-ok';
            } else if (daysInPeriod <= 100) {
                status = 'Dikkat - Sınıra Yaklaşıyorsunuz';
                statusClass = 'status-warning';
            } else {
                status = 'Kuralları Aşıyorsunuz';
                statusClass = 'status-danger';
            }
            
            summaryContainer.innerHTML = `
                <h2>Özet</h2>
                <div class="summary-item">
                    <span>Son 180 Günde Kaldığınız Süre:</span>
                    <span>${daysInPeriod} gün</span>
                </div>
                <div class="summary-item">
                    <span>Kalan Kalış Hakkı:</span>
                    <span>${90 - daysInPeriod} gün</span>
                </div>
                <div class="summary-item">
                    <span>Durum:</span>
                    <span class="${statusClass}">${status}</span>
                </div>
            `;
        }
        
        // Sonuçları göster
        function showResults(maxStayInfo, daysInPeriod) {
            const lastStayContainer = document.getElementById('lastStay');
            const remainingDays = 90 - daysInPeriod;
            
            let remainingClass = 'remaining-ok';
            if (remainingDays <= 10) {
                remainingClass = 'remaining-warning';
            }
            if (remainingDays <= 0) {
                remainingClass = 'remaining-danger';
            }
            
            if (maxStayInfo.isPossible) {
                lastStayContainer.innerHTML = `
                    <div class="future-stay">
                        <div class="future-stay-title">Ülkede Kalınan Son Tarih</div>
                        <div class="future-stay-date">${formatDate(maxStayInfo.date)}</div>
                        <div class="future-stay-days">${maxStayInfo.message}</div>
                        ${maxStayInfo.calculation ? `<div class="calculation-explanation">${maxStayInfo.calculation}</div>` : ''}
                    </div>
                    <div class="remaining-days ${remainingClass}">
                        Toplam Kalan Kalış Hakkı: ${remainingDays} gün
                    </div>
                `;
            } else {
                lastStayContainer.innerHTML = `
                    <div class="future-stay" style="background-color: #fdedec; border-color: #e74c3c;">
                        <div class="future-stay-title">Ülkede Kalınan Son Tarih</div>
                        <div class="future-stay-date" style="color: #e74c3c;">${formatDate(maxStayInfo.date)}</div>
                        <div class="future-stay-days">${maxStayInfo.message}</div>
                    </div>
                    <div class="remaining-days ${remainingClass}">
                        Toplam Kalan Kalış Hakkı: ${remainingDays} gün
                    </div>
                `;
            }
        }
        
        // Kaldığı tarihleri göster
        function showTravelHistory(travelHistory) {
            const travelHistoryContainer = document.getElementById('travelHistory');
            
            if (travelHistory.length > 0) {
                travelHistoryContainer.innerHTML = `
                    <h3>Geçmiş Seyahatler</h3>
                    ${travelHistory.map(travel => `
                        <div class="travel-history-item">
                            <div class="travel-dates">
                                ${formatDate(travel.entry)} - ${travel.hasExit ? formatDate(travel.exit) : 'Devam Ediyor'}
                                ${!travel.hasExit ? ' 🔵' : ''}
                            </div>
                            <div class="travel-days">${travel.days} gün</div>
                        </div>
                    `).join('')}
                `;
            } else {
                travelHistoryContainer.innerHTML = `
                    <h3>Geçmiş Seyahatler</h3>
                    <p>Henüz seyahat bilgisi eklenmemiş.</p>
                `;
            }
        }
        
        // Tarihi formatla
        function formatDate(date) {
            const day = String(date.getDate()).padStart(2, '0');
            const month = String(date.getMonth() + 1).padStart(2, '0');
            const year = date.getFullYear();
            return `${day}.${month}.${year}`;
        }
    </script>
</body>
</html>
