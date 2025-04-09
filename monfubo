<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>台灣國泰人壽保險商品比較分析</title>
    <style>
        body {
            font-family: 'Microsoft JhengHei', Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f9f9f9;
        }
        h1, h2, h3, h4 {
            color: #2c5282;
            margin-top: 1.5em;
        }
        h1 {
            text-align: center;
            color: #2d3748;
            margin-bottom: 30px;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 15px;
        }
        .intro-card {
            background-color: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .product-comparison {
            display: flex;
            justify-content: space-between;
            margin-bottom: 30px;
        }
        .product-card {
            width: 48%;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .product-card h3 {
            text-align: center;
            margin-top: 0;
            padding-bottom: 10px;
            border-bottom: 1px solid rgba(0,0,0,0.1);
        }
        .product-card ul {
            list-style-type: none;
            padding-left: 10px;
        }
        .product-card li {
            margin-bottom: 8px;
        }
        .product-card-old {
            background-color: #ebf8ff;
        }
        .product-card-new {
            background-color: #f0fff4;
        }
        .chart-container {
            background-color: #f7fafc;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .bar-chart {
            display: flex;
            height: 250px;
            align-items: flex-end;
            justify-content: center;
            margin-top: 20px;
            margin-bottom: 30px;
        }
        .bar-group {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0 15px;
        }
        .bar {
            width: 60px;
            border-radius: 5px 5px 0 0;
        }
        .bar-label {
            height: 40px;
            display: flex;
            align-items: center;
            text-align: center;
            font-size: 14px;
        }
        .bar-product {
            margin-top: 10px;
            font-size: 12px;
            text-align: center;
        }
        .line-chart {
            height: 300px;
            position: relative;
            margin: 30px 0;
        }
        .line-chart-inner {
            position: absolute;
            top: 0;
            left: 50px;
            right: 30px;
            bottom: 0;
        }
        .chart-legend {
            position: absolute;
            bottom: -40px;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 12px;
            flex-wrap: wrap;
        }
        .legend-item {
            display: flex;
            align-items: center;
            margin-right: 20px;
            margin-bottom: 5px;
        }
        .legend-color {
            width: 20px;
            height: 3px;
            margin-right: 5px;
        }
        .pie-chart-container {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
            flex-wrap: wrap;
        }
        .pie-chart-wrapper {
            width: 45%;
            min-width: 300px;
            margin-bottom: 30px;
        }
        .pie-chart {
            position: relative;
            width: 200px;
            height: 200px;
            margin: 0 auto;
        }
        .pie {
            position: absolute;
            width: 200px;
            height: 200px;
            border-radius: 50%;
        }
        .pie-center {
            position: absolute;
            width: 80px;
            height: 80px;
            background-color: white;
            border-radius: 50%;
            top: 60px;
            left: 60px;
        }
        .pie-legend {
            margin-top: 20px;
            font-size: 12px;
        }
        .pie-legend-item {
            display: flex;
            align-items: center;
            margin-bottom: 5px;
        }
        .pie-legend-color {
            width: 10px;
            height: 10px;
            margin-right: 5px;
        }
        .feature-box {
            background-color: #f0fff4;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 30px;
            border: 1px solid #c6f6d5;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .plan-container {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
            flex-wrap: wrap;
        }
        .plan-card {
            width: 30%;
            min-width: 250px;
            padding: 15px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            margin-bottom: 20px;
            position: relative;
        }
        .plan-card-recommended {
            transform: scale(1.05);
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            z-index: 1;
        }
        .recommended-badge {
            position: absolute;
            top: -10px;
            right: -10px;
            background-color: #ed8936;
            color: white;
            border-radius: 20px;
            padding: 5px 10px;
            font-size: 12px;
            font-weight: bold;
        }
        .benefits-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-top: 20px;
        }
        .benefit-card {
            width: 48%;
            background-color: #e6fffa;
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 15px;
        }
        .benefit-card h4 {
            color: #2c7a7b;
            margin-top: 0;
        }
        .benefit-card p {
            margin-bottom: 0;
        }
        .benefit-card-full {
            width: 100%;
        }
        .cta-box {
            background-color: #fed7d7;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 30px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .cta-box h3 {
            color: #c53030;
        }
        .cta-box ul {
            margin-top: 15px;
            list-style-type: none;
            padding-left: 0;
        }
        .cta-box li {
            margin-bottom: 10px;
        }
        .cta-button {
            background-color: #c53030;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
            font-size: 16px;
            margin-top: 20px;
        }
        .disclaimer {
            background-color: #f8f9fa;
            padding: 15px;
            border-radius: 10px;
            font-size: 12px;
            color: #718096;
        }
        .center-text {
            text-align: center;
        }
        .italic-text {
            font-style: italic;
        }
        .highlight {
            font-weight: bold;
            color: #2b6cb0;
        }
        @media (max-width: 768px) {
            .product-comparison {
                flex-direction: column;
            }
            .product-card {
                width: 100%;
                margin-bottom: 20px;
            }
            .pie-chart-wrapper {
                width: 100%;
            }
            .plan-card {
                width: 100%;
            }
            .benefit-card {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <h1>台灣國泰人壽保險商品比較分析：創世紀變額萬能壽險 vs 滿福寶</h1>

    <div class="intro-card">
        <h3 style="color: #2c5282;">客戶現況評估</h3>
        <p>您目前持有的創世紀變額萬能壽險解約金價值已達<span class="highlight">40萬元</span>，這筆資金若轉換至滿福寶利率變動型終身保險，可以獲得更穩定的保障與潛在收益。</p>
    </div>

    <h2>兩款產品核心特性對比</h2>
    <p>創世紀變額萬能壽險和滿福寶代表了兩種不同的保險理念：前者偏重投資功能，後者強調穩定保障。</p>

    <div class="product-comparison">
        <div class="product-card product-card-old">
            <h3 style="color: #2b6cb0;">創世紀變額萬能壽險</h3>
            <ul>
                <li>✓ 投資型保險，保單價值隨市場波動</li>
                <li>✓ 高投資彈性，可選擇多種投資標的</li>
                <li>✓ 風險與潛在報酬較高</li>
                <li>✓ 保障額度與投資績效連動</li>
                <li>✓ 費用結構複雜，包含投資、管理費用</li>
            </ul>
        </div>
        <div class="product-card product-card-new">
            <h3 style="color: #2f855a;">滿福寶利率變動型終身保險</h3>
            <ul>
                <li>✓ 利率變動型終身保險，價值較為穩定</li>
                <li>✓ 特定傷病、身故及完全失能保障完整</li>
                <li>✓ 風險低，穩定累積保單價值</li>
                <li>✓ 具健康促進外溢機制，保障更優化</li>
                <li>✓ 費用結構透明，成本可預期</li>
            </ul>
        </div>
    </div>

    <h2>保障內容比較分析</h2>
    <div class="chart-container">
        <h3 class="center-text">保障內容全方位比較</h3>
        <div class="bar-chart">
            <!-- 身故保障比較 -->
            <div class="bar-group">
                <div class="bar" style="background-color: #3182ce; height: 150px;"></div>
                <div class="bar-label">身故保障</div>
                <div class="bar-product">創世紀</div>
            </div>
            <div class="bar-group">
                <div class="bar" style="background-color: #38a169; height: 220px;"></div>
                <div class="bar-label">身故保障</div>
                <div class="bar-product">滿福寶</div>
            </div>

            <!-- 特定傷病比較 -->
            <div class="bar-group">
                <div class="bar" style="background-color: #3182ce; height: 90px;"></div>
                <div class="bar-label">特定傷病</div>
                <div class="bar-product">創世紀</div>
            </div>
            <div class="bar-group">
                <div class="bar" style="background-color: #38a169; height: 200px;"></div>
                <div class="bar-label">特定傷病</div>
                <div class="bar-product">滿福寶</div>
            </div>

            <!-- 保障穩定性比較 -->
            <div class="bar-group">
                <div class="bar" style="background-color: #3182ce; height: 120px;"></div>
                <div class="bar-label">保障穩定性</div>
                <div class="bar-product">創世紀</div>
            </div>
            <div class="bar-group">
                <div class="bar" style="background-color: #38a169; height: 210px;"></div>
                <div class="bar-label">保障穩定性</div>
                <div class="bar-product">滿福寶</div>
            </div>
        </div>
        <p class="center-text italic-text">滿福寶在各項保障內容上均優於創世紀變額萬能壽險，特別是在特定傷病保障方面</p>
    </div>

    <h3>滿福寶優勢說明</h3>
    <p>滿福寶提供的特定傷病保險金、身故保險金和完全失能保險金等多重保障，讓您在人生的各個階段都能獲得全面的保護。相較於創世紀變額萬能壽險，滿福寶的保障更為穩定且可預期，不會因為市場波動而影響保障額度。</p>

    <h2>風險與報酬分析</h2>
    <div class="chart-container">
        <h3 class="center-text">長期保單價值趨勢預測 (2025-2045年)</h3>
        <div class="line-chart">
            <div class="line-chart-inner">
                <!-- 水平參考線 -->
                <div style="position: absolute; left: 0; right: 0; top: 50px; height: 1px; background-color: #e2e8f0;"></div>
                <div style="position: absolute; left: 0; right: 0; top: 100px; height: 1px; background-color: #e2e8f0;"></div>
                <div style="position: absolute; left: 0; right: 0; top: 150px; height: 1px; background-color: #e2e8f0;"></div>
                <div style="position: absolute; left: 0; right: 0; top: 200px; height: 1px; background-color: #e2e8f0;"></div>
                <div style="position: absolute; left: 0; right: 0; top: 250px; height: 1px; background-color: #e2e8f0;"></div>
                
                <!-- 創世紀變額萬能壽險（高波動） -->
                <svg width="100%" height="100%" style="position: absolute; top: 0; left: 0;">
                    <path d="M0,150 L50,120 L100,180 L150,90 L200,210 L250,140 L300,220 L350,80 L400,160 L450,60 L500,180 L550,120" stroke="#3182ce" stroke-width="2" fill="none"></path>
                </svg>
                
                <!-- 滿福寶（穩定上升） -->
                <svg width="100%" height="100%" style="position: absolute; top: 0; left: 0;">
                    <path d="M0,180 L50,172 L100,164 L150,156 L200,148 L250,140 L300,132 L350,124 L400,116 L450,108 L500,100 L550,92" stroke="#38a169" stroke-width="3" fill="none"></path>
                </svg>
                
                <!-- 市場下跌情境 -->
                <svg width="100%" height="100%" style="position: absolute; top: 0; left: 0;">
                    <path d="M0,150 L50,160 L100,180 L150,200 L200,215 L250,230 L300,245 L350,260 L400,250 L450,270 L500,260 L550,270" stroke="#e53e3e" stroke-width="1" stroke-dasharray="5,5" fill="none"></path>
                </svg>
            </div>
            
            <!-- 圖例 -->
            <div class="chart-legend">
                <div class="legend-item">
                    <div class="legend-color" style="background-color: #3182ce;"></div>
                    <span>創世紀變額萬能壽險（高波動）</span>
                </div>
                <div class="legend-item">
                    <div class="legend-color" style="background-color: #38a169;"></div>
                    <span>滿福寶（穩定成長）</span>
                </div>
                <div class="legend-item">
                    <div class="legend-color" style="background-color: #e53e3e; border-top: 1px dashed #e53e3e;"></div>
                    <span>市場下跌情境</span>
                </div>
            </div>
        </div>
        <p class="center-text italic-text">在市場波動情況下，滿福寶提供穩定的價值成長，而創世紀變額萬能壽險則可能面臨顯著波動</p>
    </div>

    <h3>風險因素分析</h3>
    <p>在目前全球經濟不確定性增加的2025年環境下，滿福寶的利率變動型設計提供更穩健的保障。創世紀變額萬能壽險雖然在市場上漲時可能獲得較高回報，但在市場下跌時，您的保單價值和保障可能會大幅縮水。</p>

    <h2>保費配置與成本效益分析</h2>
    <div class="chart-container">
        <h3 class="center-text">保費配置比較</h3>
        <div class="pie-chart-container">
            <div class="pie-chart-wrapper">
                <h4 class="center-text" style="color: #2b6cb0;">創世紀變額萬能壽險</h4>
                <div class="pie-chart">
                    <div class="pie" style="background: conic-gradient(#3182ce 0% 25%, #4299e1 25% 42%, #63b3ed 42% 65%, #90cdf4 65% 85%, #bee3f8 85% 100%);"></div>
                    <div class="pie-center"></div>
                </div>
                <div class="pie-legend">
                    <div class="pie-legend-item">
                        <div class="pie-legend-color" style="background-color: #3182ce;"></div>
                        <span>保險成本 (25%)</span>
                    </div>
                    <div class="pie-legend-item">
                        <div class="pie-legend-color" style="background-color: #4299e1;"></div>
                        <span>投資費用 (17%)</span>
                    </div>
                    <div class="pie-legend-item">
                        <div class="pie-legend-color" style="background-color: #63b3ed;"></div>
                        <span>管理費用 (23%)</span>
                    </div>
                    <div class="pie-legend-item">
                        <div class="pie-legend-color" style="background-color: #90cdf4;"></div>
                        <span>保障成分 (20%)</span>
                    </div>
                    <div class="pie-legend-item">
                        <div class="pie-legend-color" style="background-color: #bee3f8;"></div>
                        <span>實際投資部分 (15%)</span>
                    </div>
                </div>
            </div>
            <div class="pie-chart-wrapper">
                <h4 class="center-text" style="color: #2f855a;">滿福寶利率變動型終身保險</h4>
                <div class="pie-chart">
                    <div class="pie" style="background: conic-gradient(#38a169 0% 60%, #48bb78 60% 85%, #9ae6b4 85% 100%);"></div>
                    <div class="pie-center"></div>
                </div>
                <div class="pie-legend">
                    <div class="pie-legend-item">
                        <div class="pie-legend-color" style="background-color: #38a169;"></div>
                        <span>保障成分 (60%)</span>
                    </div>
                    <div class="pie-legend-item">
                        <div class="pie-legend-color" style="background-color: #48bb78;"></div>
                        <span>儲蓄成分 (25%)</span>
                    </div>
                    <div class="pie-legend-item">
                        <div class="pie-legend-color" style="background-color: #9ae6b4;"></div>
                        <span>費用 (15%)</span>
                    </div>
                </div>
            </div>
        </div>
        <p class="center-text italic-text">滿福寶的保費更多用於實際保障，費用結構更加透明且合理</p>
    </div>

    <h3>成本效益優勢</h3>
    <p>滿福寶的保費配置更加重視保障功能，高達60%的保費直接用於保障成分，相比創世紀變額萬能壽險的20%保障成分高出三倍。此外，滿福寶的費用結構更加簡單透明，僅佔總保費的15%，而創世紀變額萬能壽險的各項費用合計高達40%以上。</p>

    <h2>健康促進外溢機制—滿福寶獨家優勢</h2>
    <div class="feature-box">
        <h3 class="center-text" style="color: #2f855a;">滿福寶健康促進回饋機制</h3>
        <p>滿福寶的外溢型設計結合了健康促進計劃，當您符合健康標準時，可獲得以下額外權益：</p>
        <ul style="margin-top: 15px;">
            <li>保險成本最高可折減<strong>20%</strong></li>
            <li>透過「FitBack健康吧」健康計劃獲得額外保障</li>
            <li>達到特定會員等級時享有保險權益提升</li>
            <li>健康生活方式帶來雙重收益：改善健康狀況並獲得保險回饋</li>
        </ul>
        <p style="margin-top: 15px; font-style: italic;">創世紀變額萬能壽險並無類似健康促進機制</p>
    </div>

    <h2>客戶轉換方案建議</h2>
    <div class="chart-container">
        <h3 class="center-text">專屬轉換方案</h3>
        <p>根據您目前持有的創世紀變額萬能壽險解約金40萬元，我們建議以下轉換方案：</p>
        <div class="plan-container">
            <div class="plan-card">
                <h4 style="color: #2b6cb0; text-align: center;">基本方案</h4>
                <ul style="list-style-type: none; padding-left: 0;">
                    <li style="margin-bottom: 10px;">● 投入金額：25萬元</li>
                    <li style="margin-bottom: 10px;">● 保障額度：150萬元</li>
                    <li style="margin-bottom: 10px;">● 特定傷病保障：75萬元</li>
                    <li>● 剩餘資金可靈活運用</li>
                </ul>
            </div>
            <div class="plan-card plan-card-recommended">
                <h4 style="color: #2c5282; text-align: center;">推薦方案</h4>
                <div class="recommended-badge">推薦</div>
                <ul style="list-style-type: none; padding-left: 0;">
                    <li style="margin-bottom: 10px;">● 投入金額：35萬元</li>
                    <li style="margin-bottom: 10px;">● 保障額度：250萬元</li>
                    <li style="margin-bottom: 10px;">● 特定傷病保障：125萬元</li>
                    <li>● 健康促進折減最高可達20%</li>
                </ul>
            </div>
            <div class="plan-card">
                <h4 style="color: #2b6cb0; text-align: center;">全額轉換方案</h4>
                <ul style="list-style-type: none; padding-left: 0;">
                    <li style="margin-bottom: 10px;">● 投入金額：40萬元</li>
                    <li style="margin-bottom: 10px;">● 保障額度：300萬元</li>
                    <li style="margin-bottom: 10px;">● 特定傷病保障：150萬元</li>
                    <li>● 最大化保障與利益</li>
                </ul>
            </div>
        </div>
    </div>

    <h2>客戶轉換效益總結</h2>
    <div class="chart-container">
        <h3 class="center-text">轉換滿福寶的五大優勢</h3>
        <div class="benefits-grid">
            <div class="benefit-card">
                <h4>1. 保障更穩定可靠</h4>
                <p>不受市場波動影響，保障金額固定且可預期，為家人提供更安心的保護。</p>
            </div>
            <div class="benefit-card">
                <h4>2. 特定傷病保障更全面</h4>
                <p>滿福寶提供更完整的特定傷病保障，在健康風險來臨時提供財務支持。</p>
            </div>
            <div class="benefit-card">
                <h4>3. 健康促進回饋機制</h4>
                <p>透過健康生活方式獲得保險成本折減，最高可達20%，創造健康與財務雙贏。</p>
            </div>
            <div class="benefit-card">
                <h4>4. 費用結構更透明</h4>
                <p>滿福寶的費用僅佔總保費的15%，大幅低於創世紀變額萬能壽險的40%以上。</p>
            </div>
            <div class="benefit-card benefit-card-full">
                <h4>5. 符合2025年市場環境</h4>
                <p>在當前全球經濟不確定性增加的環境下，滿福寶的穩健設計更能抵禦市場波動風險，為您的財務規劃提供堅實基礎。</p>
            </div>
        </div>
    </div>

    <h2>行動方案</h2>
    <div class="cta-box">
        <h3>限時優惠</h3>
        <p style="font-weight: bold;">即日起至2025年6月30日，轉換滿福寶享有以下專屬優惠：</p>
        <ul>
            <li>● 首年保費折減5%</li>
            <li>● 免費健康檢查一次</li>
            <li>● FitBack健康吧會員升級</li>
            <li>● 提供個人化財務規劃諮詢服務</li>
        </ul>
        <button class="cta-button">立即預約轉換諮詢</button>
    </div>

    <div class="disclaimer">
        <p><strong>免責聲明：</strong>本文件僅供參考，不構成任何投資或保險建議。實際保險內容及權益以保險契約條款為準。在做出任何保險決策前，請務必詳閱保險商品說明書及保單條款，並諮詢專業保險顧問。</p>
    </div>
</body>
</html>
