<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>볼카노골프앤리조트: 회생을 향한 길</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans KR', sans-serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 350px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 400px;
            }
        }
        .flow-arrow {
            font-size: 2rem;
            color: #FFA600;
            line-height: 1;
            align-self: center;
            margin: 0 1rem;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <div class="container mx-auto p-4 md:p-8">
        
        <header class="text-center mb-12">
            <h1 class="text-4xl md:text-5xl font-black text-[#003F5C] mb-2">볼카노골프앤리조트 회생 계획 분석</h1>
            <p class="text-lg text-gray-600">삼일회계법인 조사보고서 기반 핵심 인사이트</p>
        </header>

        <main>
            <section id="current-status" class="mb-12">
                <div class="bg-white rounded-lg shadow-xl p-6 md:p-8 border-l-8 border-[#F95D6A]">
                    <h2 class="text-2xl font-bold text-[#003F5C] mb-4">현재의 기로: 기업가치 평가 결과</h2>
                    <p class="mb-6">조사위원의 평가에 따르면, 현재 시점에서 볼카노골프앤리조트의 사업을 청산하는 것이 계속 운영하는 것보다 경제적으로 더 유리한 것으로 나타났습니다. 이는 회사가 심각한 재무적 위기에 처해있음을 의미하며, 회생절차의 개시가 불가피했음을 보여줍니다.</p>
                    <div class="chart-container">
                        <canvas id="valueComparisonChart"></canvas>
                    </div>
                    <div class="mt-6 text-center">
                        <p class="text-xl font-bold">청산가치 대비 계속기업가치 <span class="text-3xl font-black text-[#D45087]">77,393백만원</span> 부족</p>
                        <p class="text-sm text-gray-500">이는 즉각적인 개선 조치가 없다면 청산이 합리적인 선택임을 시사합니다.</p>
                    </div>
                </div>
            </section>

            <section id="turnaround-plan" class="mb-12">
                <h2 class="text-3xl font-bold text-center text-[#003F5C] mb-8">희망의 불씨: 채무자의 사업 정상화 계획</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white rounded-lg shadow-xl p-8 transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl font-black text-[#FFA600] mb-4">①</div>
                        <h3 class="text-xl font-bold text-[#665191] mb-2">리조트 신규 분양</h3>
                        <p>새로운 리조트 상품을 시장에 공급하여 신규 자금을 유치하고 현금 흐름을 개선하는 것을 목표로 합니다. 이는 회사의 핵심 영업활동을 재개하고 수익성을 회복하기 위한 첫걸음입니다.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-xl p-8 transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl font-black text-[#FFA600] mb-4">②</div>
                        <h3 class="text-xl font-bold text-[#665191] mb-2">기존 회원 권리 감축</h3>
                        <p>회사의 과도한 부채 부담을 줄이기 위해 기존 회원들의 권리를 일부 조정하는 방안입니다. 이는 채권자들과의 고통 분담을 통해 재무 구조를 건실하게 만들기 위한 불가피한 조치입니다.</p>
                    </div>
                </div>
                 <p class="text-center mt-6 text-gray-600">단, 조사위원은 위 계획 실행을 위한 <span class="font-bold">자금 확보 가능성이 불확실</span>하여 현재 가치 평가에는 반영하지 않았습니다.</p>
            </section>

            <section id="potential" class="mb-12">
                 <div class="bg-white rounded-lg shadow-xl p-6 md:p-8 border-l-8 border-[#2F4B7C]">
                    <h2 class="text-2xl font-bold text-[#003F5C] mb-4">잠재적 반전: 사업 계획 성공 시나리오</h2>
                    <p class="mb-6">만약 채무자가 계획한 자금을 성공적으로 확보하여 사업 계획을 이행할 경우, 계속기업가치는 극적으로 반전될 수 있습니다. 83,302백만원의 가치 증대가 예상되며, 이는 청산가치를 넘어서는 수치로 기업 회생의 청신호가 될 것입니다.</p>
                    <div class="chart-container">
                        <canvas id="potentialValueChart"></canvas>
                    </div>
                     <div class="mt-6 text-center">
                        <p class="text-xl font-bold">예상 계속기업가치, 청산가치를 <span class="text-3xl font-black text-[#003F5C]">6,205백만원</span> 초과</p>
                        <p class="text-sm text-gray-500">성공적인 자금 조달이 기업 회생의 핵심 열쇠임을 보여줍니다.</p>
                    </div>
                </div>
            </section>

            <section id="recommendation">
                <h2 class="text-3xl font-bold text-center text-[#003F5C] mb-8">조사위원의 최종 권고: 회생을 위한 단계적 접근</h2>
                <div class="bg-white rounded-lg shadow-xl p-8">
                    <div class="flex flex-col md:flex-row items-center justify-center">
                        <div class="text-center p-4 border-2 border-dashed border-[#665191] rounded-lg m-2 flex-1">
                            <h3 class="text-lg font-bold text-[#665191]">1단계: 자력 회생 기회 부여</h3>
                            <p class="mt-2">대주주에게 일정 기간 <span class="font-extrabold">유상증자</span>를 통해 자금을 확보할 기회를 제공합니다.</p>
                        </div>
                        
                        <div class="transform rotate-90 md:rotate-0 flow-arrow">➔</div>

                        <div class="text-center p-4 border-2 border-dashed border-gray-400 rounded-lg m-2 flex-1">
                            <h3 class="text-lg font-bold text-gray-600]">2단계 (1단계 실패 시)</h3>
                            <p class="mt-2 font-extrabold text-[#D45087]">인가 전 M&A 추진</p>
                            <p class="mt-2">외부 투자 유치를 통해 일시적인 자금을 확보하여 채권자 피해를 최소화하고 회생을 도모합니다.</p>
                        </div>
                    </div>
                </div>
            </section>
        </main>
        
        <footer class="text-center mt-12 py-6 border-t">
            <p class="text-sm text-gray-500">본 자료는 '주식회사 볼카노골프앤리조트 조사보고서(요약)'을 기반으로 제작된 시각화 자료입니다.</p>
        </footer>
    </div>

    <script>
        const FONT_COLOR = '#003F5C';
        const GRID_COLOR = '#e0e0e0';
        const PALETTE = {
            darkBlue: '#003F5C',
            purple: '#665191',
            pink: '#D45087',
            red: '#F95D6A',
            orange: '#FF7C43',
            yellow: '#FFA600'
        };

        const tooltipTitleCallback = (tooltipItems) => {
            const item = tooltipItems[0];
            let label = item.chart.data.labels[item.dataIndex];
            return Array.isArray(label) ? label.join(' ') : label;
        };

        const commonChartOptions = {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                legend: {
                    position: 'top',
                    labels: {
                        color: FONT_COLOR,
                        font: { size: 14 }
                    }
                },
                tooltip: {
                    callbacks: {
                        title: tooltipTitleCallback,
                        label: function(context) {
                            let label = context.dataset.label || '';
                            if (label) {
                                label += ': ';
                            }
                            if (context.parsed.y !== null) {
                                label += new Intl.NumberFormat('ko-KR').format(context.parsed.y) + ' 백만원';
                            }
                            return label;
                        }
                    },
                    backgroundColor: 'rgba(0, 0, 0, 0.8)',
                    titleFont: { size: 16 },
                    bodyFont: { size: 14 },
                    padding: 10
                }
            },
            scales: {
                x: {
                    ticks: { 
                        color: FONT_COLOR,
                        font: { size: 12, weight: 'bold' }
                    },
                    grid: { display: false }
                },
                y: {
                    ticks: {
                        color: FONT_COLOR,
                        font: { size: 12 },
                        callback: function(value) {
                            return new Intl.NumberFormat('ko-KR').format(value);
                        }
                    },
                    grid: { color: GRID_COLOR },
                    title: {
                        display: true,
                        text: '금액 (백만원)',
                        color: FONT_COLOR,
                        font: { size: 14, weight: 'bold'}
                    }
                }
            }
        };

        function createValueComparisonChart() {
            const ctx = document.getElementById('valueComparisonChart').getContext('2d');
            new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: ['계속기업가치', '청산가치'],
                    datasets: [{
                        label: '가치 평가 (백만원)',
                        data: [-35296, 42097],
                        backgroundColor: [PALETTE.red, PALETTE.darkBlue],
                        borderColor: ['#FFFFFF'],
                        borderWidth: 2
                    }]
                },
                options: { ...commonChartOptions }
            });
        }
        
        function createPotentialValueChart() {
            const ctx = document.getElementById('potentialValueChart').getContext('2d');
            new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: ['예상 계속기업가치', '청산가치'],
                    datasets: [{
                        label: '사업계획 성공 시 가치 비교 (백만원)',
                        data: [48006, 42097],
                        backgroundColor: [PALETTE.darkBlue, PALETTE.purple],
                        borderColor: ['#FFFFFF'],
                        borderWidth: 2
                    }]
                },
                options: {
                    ...commonChartOptions,
                    scales: {
                        ...commonChartOptions.scales,
                        y: {
                           ...commonChartOptions.scales.y,
                           beginAtZero: true
                        }
                    }
                }
            });
        }

        window.onload = function() {
            createValueComparisonChart();
            createPotentialValueChart();
        };
    </script>
</body>
</html>
