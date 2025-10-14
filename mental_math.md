# 🧠 ENHANCED MENTAL‑MATH CHEAT‑SHEET

*(Copy‑&‑paste the whole thing into any plain‑text note – the tables stay aligned in most editors.  Feel free to reorder the sections to match the tricks you use most.)*  

---

## 📖 HOW TO READ THIS SHEET  

| Symbol | Meaning |
|--------|---------|
| **Shortcut** | The name you’ll call the trick when you practice it. |
| **Why it works** | One‑line intuition – helps you remember the rule. |
| **Core rule / formula** | The algebraic statement you apply. |
| **Primary example** | A “starter” problem that shows the whole flow. |
| **Extra examples** | Quick variations to test the rule. |
| **Mnemonic** | Tiny phrase or picture that sticks in memory. |

**Practice loop** – Pick a shortcut → do 8‑10 problems only with that shortcut → time yourself (≤ 5 s once warm) → check → move on.  Mix two shortcuts together once you’re fluent.

---

## 1️⃣ ADDITION & SUBTRACTION  

| # | Shortcut | Why it works | Core rule / formula | Primary example | Extra examples | Mnemonic |
|---|----------|--------------|---------------------|-----------------|----------------|----------|
| 1 | **Round‑Up & Fix‑It (Add)** | Replace each addend by a round neighbour, add the easy numbers, then subtract the “extra” you added. | \((a+b) = (a+Δ_a)+(b+Δ_b) - (Δ_a+Δ_b)\) | **73 + 28** → 80 + 30 = 110 – 9 = **101** | 164 + 279 → 170 + 280 = 450 – 7 = 443 • 52 + 399 → 50 + 400 = 450 – 3 = 447 | “Round up, add, then roll back.” |
| 2 | **Round‑Up & Fix‑It (Sub)** | Round the subtrahend up, subtract the round number, then add the amount you rounded. | \(a-b = a-(b+Δ) + Δ\) | **382 − 149** → 382 − 150 = 232 + 1 = **233** | 560 − 237 → 560 − 240 = 320 + 3 = 323 • 1000 − 68 → 1000 − 70 = 930 + 2 = 932 | “Up‑then‑down, tidy‑up.” |
| 3 | **All‑From‑9, Last‑From‑10 (1000‑sub)** | Complement each digit to 9, the final digit to 10 → 10‑complement of the number. | \(1000-abc = (9-a)(9-b)(10-c)\) | **1000 − 274** → **726** | 1000 − 639 → 361 • 1000 − 845 → 155 | “9‑9‑10” |
| 4 | **Subtract from a “nice” round number** | Break the round number into two parts (hundreds + complement) so you only subtract a small piece. | \(R - N = (R-100k) + (100k - N)\) (choose *k* for a close hundred) | **500 − 237** → 500‑200 = 300; 100‑37 = 63 → **363** | 800 − 468 → 800‑400 = 400; 100‑68 = 32 → **432** • 300‑174 → 300‑200 = 100; 100‑74 = 26 → **126** | “Chunk the round.” |
| 5 | **Quick 100‑subtraction** | Take away the tens, then add back the amount you overshoot. | 100 − a = (100 − nearest 10 multiple) + overshoot | **100 − 68** → 100‑70 = 30 + 2 = **32** | 100‑54 → 100‑50 = 50‑4 = 46 • 100‑87 → 100‑90 = 10 + 3 = 13 | “Drop‑tens, add‑overshoot.” |
| 6 | **Casting‑out‑nines (sum check)** | Digital root is preserved mod 9: dr(a)+dr(b) ≡ dr(a+b) (mod 9). | dr(n) = sum of digits repeated to one digit (treat 9 as 0) | 73 + 28 = 101 → dr(73)=1, dr(28)=1 → 1+1=2 → dr(101)=2 ✔️ | 145 + 276 = 421 → dr=1 and 6 → 1+6=7 → dr(421)=7 ✔️ | “Nines don’t change sums.” |
| 7 | **“Borrow‑less” subtraction** (when the subtrahend digit ≤ minuend digit) | No borrowing → subtract each column directly. Good for quick mental checks. | Direct column subtraction | **842 − 531** → 8‑5=3, 4‑3=1, 2‑1=1 → **311** | 970‑258 → 7‑2=5, 9‑5=4, 0‑8 (borrow) → not‑borrow‑less; use only when safe. | “Simple column walk.” |
| 8 | **Add‑then‑subtract 5’s** (for many‑digit sums) | Adding 5 to each number makes the last digit 0, then subtract the total number of addends × 5. | \(\sum a_i = \sum (a_i+5) - 5n\) | 47 + 68 + 99 → (52 + 73 + 104) − 15 = 229 − 15 = **214** | 23 + 57 + 82 → (28 + 62 + 87) − 15 = 177 − 15 = **162** | “5‑up, 5‑down.” |

---

## 2️⃣ MULTIPLICATION  

| # | Shortcut | Why it works | Core rule / pattern | Primary example | Extra examples | Mnemonic |
|---|----------|--------------|---------------------|-----------------|----------------|----------|
| 1 | **× 5** (half of × 10) | Multiply by 10 then halve. | \(n·5 = (n·10) ÷ 2\) | **63 × 5** → 630 ÷ 2 = **315** | 84 × 5 = 420; 27 × 5 = 135 | “10‑then‑½.” |
| 2 | **× 9** (× 10 − n) | 9 = 10 − 1. | \(n·9 = (n·10) - n\) | **57 × 9** → 570 − 57 = **513** | 34 × 9 = 306; 123 × 9 = 1107 | “Ten‑take‑one.” |
| 3 | **× 11** (two‑digit) | Write first digit, add the two digits, write last digit; carry if needed. | \(ab·11 = a\;(a+b)\;b\) (carry) | **64 × 11** → 6\|10\|4 → write 6, 10→0 carry 1 → 6+1=7 → **704** | 27 × 11 = 297; 85 × 11 = 935 | “Middle sum magic.” |
| 4 | **× 12** (10 + 2) | Split 12 into 10 + 2; add the double. | \(n·12 = n·10 + n·2\) | **47 × 12** → 470 + 94 = **564** | 63 × 12 = 756; 19 × 12 = 228 | “Ten plus two.” |
| 5 | **Doubling ↔ Halving** | Move a factor of 2 from one operand to the other, product unchanged. | If one factor even → halve it, double the other. | **24 × 25** → 12 × 50 = **600** | 68 × 15 → 34 × 30 = 1020 | “Shift the 2.” |
| 6 | **Square numbers ending in 5** | \((10n+5)² = 100n(n+1)+25\). The result always ends **25**; the left part is n × (n+1). | \((n5)² = n·(n+1)‖25\) | **65²** → 6·7 = 42 → **4225** | 85² = 7225; 95² = 9025 | “5‑square = n × (n+1) ‖ 25.” |
| 7 | **Difference of Squares (symmetrical)** | For a pair equally spaced around a centre *c*: \((c-d)(c+d)=c²‑d²\). | \((c-d)(c+d)=c²-d²\) | **41 × 59** → c=50, d=9 → 2500‑81 = **2419** | 37 × 63 → c=50,d=13 → 2500‑169=2331; 68 × 72 → c=70,d=2 → 4900‑4=4896 | “Around a centre.” |
| 8 | **Numbers near a base (B ± x)** | \((B+x)(B‑x)=B²‑x²\). Choose B=10, 100, 1000… that makes *x* tiny. | \((B±x)(B∓x)=B²‑x²\) | **97 × 103** → B=100, x=3 → 10000‑9 = **9991** | 86 × 114 → B=100, x=14 → 10000‑196 = 9804; 299 × 301 → B=300, x=1 → 90 000‑1=89 999 | “Base‑plus‑minus.” |
| 9 | **× 25** (100 ÷ 4) | Multiply by 100 (add two zeros) then divide by 4 (or halve twice). | \(n·25 = (n·100) ÷ 4\) | **16·25** → 1600 ÷ 4 = **400** | 33·25 = 825; 78·25 = 1950 | “Quarter of 100.” |
|10| **Cross‑Add (2‑digit × 2‑digit)** | Expand \((10p+q)(10r+s)=100pr+10(ps+qr)+qs\). Compute three small parts, stitch. | Hundreds = p·r; Tens = p·s + q·r; Units = q·s | **46 × 57** → 4·5=20 (hundreds) → 4·7+5·6=58 (tens) → 6·7=42 (units) → **2622** | 23·47 → 8 (800) + 26 (260) + 21 = 1081 | “Hundreds‑tens‑units.” |
|11| **× 99 (or 999…)** | Multiply by 100 (or 1000) then subtract the original. | \(n·99 = n·100 - n\) | **47·99** → 4700‑47 = **4653** | 84·99 = 8316; 12·999 = 11988 | “One‑less‑hundred.” |
|12| **× 101** | Write the number, then repeat its middle digit(s). | \(n·101 = n·100 + n\) | **34·101** → 3400 + 34 = **3434** | 57·101 = 5757 | “Add a zero, add back.” |
|13| **Average‑and‑Difference (a ± d)** | Same as #7 but stresses the “average” a. | \((a-d)(a+d) = a²-d²\) | **48 × 52** → a=50,d=2 → 2500‑4 = **2496** | 69·71 → a=70,d=1 → 4900‑1=4899 | “Midpoint square minus d².” |
|14| **Fast × 7 (× 8 − n)** | 7 = 8 − 1. Multiply by 8 (shift left three times) then subtract the original. | \(n·7 = n·8 - n\) | **47·7** → 47·8=376 − 47 = **329** | 23·7 = 184‑23=161 | “Eight‑minus‑one.” |
|15| **Fast × 13 (× 10 + × 3)** | 13 = 10 + 3. Easy because × 10 is a shift, × 3 is double + original. | \(n·13 = n·10 + n·3\) | **26·13** → 260 + 78 = **338** | 57·13 = 570 + 171=741 | “Ten‑plus‑three.” |
|16| **Multiplying two‑digit by 25** | 25 = 100 ÷ 4. Multiply by 100 then quarter (half‑half). | \(ab·25 = (ab·100) ÷ 4\) | **64·25** → 6400 ÷ 4 = **1600** | 37·25 = 3700 ÷ 4 = 925 | “Quarter of a hundred‑fold.” |
|17| **Cross‑multiply for fractions** (a/b × c/d) | Multiply across, then simplify if possible. | \(\frac{a}{b}·\frac{c}{d} = \frac{ac}{bd}\) | \(\frac{7}{12}·\frac{4}{9}\) → \(28/108 = 7/27\) | \(\frac{5}{8}·\frac{3}{10}\) → 15/80 = 3/16 | “Across is easy.” |
|18| **Multiplying by 75** | 75 = 3 × 25. Use the × 25 rule, then triple. | \(n·75 = (n·25)·3\) | **24·75** → 24·25=600 → × 3 = **1800** | 13·75 = 325·3 = 975 | “Three‑quarters = 3×25.” |
|19| **Multiplying by 125** | 125 = 5 × 25. Use × 25 then × 5 (or × 5 then × 25). | \(n·125 = (n·25)·5\) | **32·125** → 32·25=800 → × 5 = **4000** | 7·125 = 175·5 = 875 | “Five‑quarters = 5×25.” |
|20| **Fast “× 99 + 1” (i.e., × 100 − n + 1)** | Useful for numbers like 101·99 = 9999. | \(n·99+1 = n·100 - n + 1\) | **57·99+1** → 5700‑57+1=**5644** | 23·99+1 = 2300‑23+1=**2278** | “99‑plus‑1 = 100‑minus‑n+1.” |

---

## 3️⃣ DIVISION, PERCENTAGES & CONVERSIONS  

| # | Shortcut | Why it works | Core rule | Primary example | Extra examples | Mnemonic |
|---|----------|--------------|-----------|-----------------|----------------|----------|
| 1 | **÷ 5** (× 2 then shift) | 5 = 10 ÷ 2. Multiply by 2, then move decimal left. | \(n ÷ 5 = (n·2) ÷ 10\) | **275 ÷ 5** → 275·2 = 550 → 55.0 | 93÷5 = 18.6; 410÷5 = 82 | “Double‑then‑dot.” |
| 2 | **÷ 9** (digit‑sum estimate) | Remainder = digit‑sum mod 9. Quotient ≈ (digit‑sum)÷9, then adjust. | Use digit sum to get rough quotient, then correct. | **462 ÷ 9** → 9×50=450, remainder 12 → **51 ⅓** | 81÷9 = 9; 199÷9 = 22 ⅑ | “9‑sum‑rule.” |
| 2 | **÷ 9** (near‑multiple method) | Use a nearby multiple of 9; remainder equals n mod 9 (digit‑sum mod 9) for a quick check. | Pick 9·k close to n → n = 9k + r → quotient = k and remainder r. | **462 ÷ 9** → 9×50=450, r=12 → **50 r 12 = 50 + 12/9 = 51 ⅓** | 81÷9=9; 199÷9 → 9×22=198, r=1 → **22 ⅑** | “Nine‑multiple and remainder.” |
| 3 | **% of a number (10 %‑based)** | 10 % = move decimal left one place. Build any percent from 10 % and 5 % (half of 10 %). | \(p\%·N =\) sum of appropriate 10 % pieces. | **15 % of 250** → 10 % = 25; 5 % = 12.5 → **37.5** | 27 % of 640 → 20 % = 128; 7 % ≈ 64‑19.2 = 44.8 → 172.8 | “Ten‑base percent.” |
| 4 | **Tip / Discount (k × 10 %)** | Multiply the 10 % amount by *k* (k=1,2,3…) | Discount = \(k·10\%·price\) | **20 % off $57.90** → 10 % = 5.79 → ×2 = 11.58 → **$46.32** | 15 % tip on $84 → 10 % = 8.40; 5 % = 4.20 → **12.60** | “k‑times‑ten‑percent.” |
| 5 | **°F → °C (quick)** | Approximate \(C≈(F‑30)/2\) (since exact is \((F‑32)·5/9\)). | \(C ≈ (F‑30)/2\) | **95 °F** → (95‑30)=65 ÷ 2 = **32.5 °C** (real 35 °C) | 68 °F → 19 °C (real 20 °C) | “Minus 30, halve.” |
| 6 | **°C → °F (quick)** | Approximate \(F≈2C+30\). | \(F ≈ 2C + 30\) | **20 °C** → 2·20+30 = **70 °F** (real 68 °F) | 35 °C → 100 °F (real 95 °F) | “Double‑plus‑30.” |
| 7 | **Square a multiple of 10** | \((10a)² = 100·a²\). Just square the single‑digit *a* and add two zeros. | \((10a)² = a²·100\) | **70²** → 7²=49 → **4 900** | 90² = 8 100; 30² = 900 | “Tens‑square = a² 00.” |
| 8 | **Cube via (a ± b)³** | Binomial expansion keeps numbers small when *b* is tiny. | \((a ± b)³ = a³ ± 3a²b + 3ab² ± b³\) | **12³** → (10+2)³ = 1000 + 600 + 120 + 8 = **1 728** | 19³ → (20‑1)³ = 8000‑1200+60‑1 = **6 859** | “Base‑plus‑offset cube.” |
| 9 | **÷ 25** (or 0.04) | 25 = 100 ÷ 4. Multiply by 4, then shift two decimal places left. | \(n ÷ 25 = (n·4) ÷ 100\) | **68 ÷ 25** → 68·4 = 272 → 2.72 | 125÷25 = 5; 200÷25 = 8 | “Quarter‑of‑hundred.” |
|10| **÷ 12** | 12 = 3 × 4. Divide by 3 then by 4 (or reverse). Both steps are easy. | \(n ÷ 12 = (n ÷ 3) ÷ 4\) | **144 ÷ 12** → ÷ 3 = 48 → ÷ 4 = **12** | 252÷12 → ÷ 3 = 84 → ÷ 4 = 21 | “Three‑then‑four.” |
|11| **÷ 7** (× 7 ≈ × 8 − n) | 7 = 8 − 1; multiply by 8 (shift left three) then subtract the original. | \(n÷7 ≈ (n·8 ÷ 7) - (n ÷ 7)\) – practical for *n* up to 1000: estimate then adjust. | **84÷7** → 84·8=672 ÷ 7=96 → subtract 12 (since we added one extra 84) → **12** | 196÷7 → 200‑4=196 → 28 | “Eight‑minus‑one method.” |
|11| **÷ 7 (nearest‑multiple method)** | Think in 70s: 7×10=70. Use 70‑chunks to get close, then adjust the small remainder. | Choose k so 70·k ≈ 10·n → start with 10k, refine to exact q where n = 7q + r; answer = q with remainder r. | **196÷7** → 7×28=196 → **28** | **205÷7** → 7×29=203, r=2 → **29 r 2 = 29 2/7 ≈ 29.285** | “Think in 70s.” |
|12| **÷ 3** (quick) | Divide by 3 = divide by 6 then double, or split into 30 % + remainder. | \(n÷3 = (n÷6)·2\) | **84÷3** → 84÷6=14 → × 2 = **28** | 99÷3 = 33; 145÷3≈48 + 1/3 | “Half‑of‑sixth.” |
|13| **Fraction → %** | Multiply by 100, then simplify the mental division. | \(\frac{a}{b}·100\%\) | \(\frac{3}{8} = 0.375 → 37.5\%\) | \(\frac{5}{12}≈41.67\%\) | “Hundred‑times.” |
|14| **% → Fraction** | Write percent over 100 and reduce. | \(p\% = \frac{p}{100}\) | **45 %** → 45/100 = 9/20 | **125 %** → 125/100 = 5/4 | “Percent‑over‑hundred.” |
|15| **Rapid √(near‑square)** | For N≈a², use \(\sqrt{N}≈a+ \frac{N-a²}{2a}\). Works well when the difference is ≤ 2a. | \(\sqrt{N}≈a+ \frac{Δ}{2a}\) where Δ = N‑a² | √(102 ≈ 10²) → a=10, Δ=2 → 10+2/(20)=10.1 | √(250 ≈ 15²) → a=15, Δ=25 → 15+25/30≈15.83 | “Base‑plus‑Δ/2a.” |

**Quick‑percentage cheat‑card (keep in mind):**  

| % | Shortcut |
|---|----------|
| 1 % | Move decimal two places left |
| 5 % | Half of 10 % |
| 10 % | Move decimal one place left |
| 15 % | 10 % + 5 % |
| 20 % | Double 10 % |
| 25 % | Quarter the number |
| 33 % | Roughly one‑third (÷ 3) |
| 50 % | Halve |
| 75 % | 50 % + 25 % |
| 90 % | 100 % − 10 % |

---

## 4️⃣ SQUARES & CUBES (FAST FORMULAS)  

| # | Shortcut | Why it works | Core formula | Primary example | Extra examples | Mnemonic |
|---|----------|--------------|--------------|-----------------|----------------|----------|
| 1 | **Square < 50 (using 50‑n)** | \((50‑n)² = 2500 - 100n + n²\). 2500 is easy, then adjust. | \((50-n)² = 2500 - 100n + n²\) | **43²** → 2500‑4300? Wait: 2500‑4300 (typo) → Actually 2500‑4300? Hold on – correct: 2500‑4300? Let's correct: 2500‑100·43=2500‑4300? No, 100·43=4300 > 2500, so better use 45‑2: \((45-2)² = 2025‑180+4=1850\). Use 45‑n for numbers 40‑49. | 42² → (45‑3)² = 2025‑270+9 = **1764**; 48² → (50‑2)² = 2500‑200+4 = **2304** | “45‑base for 40‑49.” |
| 1 | **Square < 50 (using 50‑n)** | \((50−n)² = 2500 − 100n + n²\). 2500 is easy, then adjust. | \((50-n)² = 2500 - 100n + n²\) | **43²** → n=7 → 2500−700+49 = **1849** | 42² → (50−8)² = 2500−800+64 = **1764**; 48² → (50−2)² = 2500−200+4 = **2304** | “50‑base for 40‑49.” |
| 2 | **Square 50‑99 (using 100‑n)** | \((100-n)² = 10 000 - 200n + n²\). | \((100-n)² = 10 000 - 200n + n²\) | **73²** → 10 000‑14 600+5 329 = **5 329** | 86² → 10 000‑17 200+7 396 = **5 196** | “Minus from 100.” |
| 2 | **Square 50‑99 (using 100‑n)** | \((100−n)² = 10 000 − 200n + n²\). | \((100-n)² = 10 000 - 200n + n²\) | **73²** → n=27 → 10 000−5 400+729 = **5 329** | **86²** → n=14 → 10 000−2 800+196 = **7 396** | “Minus from 100.” |
| 3 | **Square numbers ending in 5** (already in multiplication) | \((10n+5)² = 100n(n+1)+25\). | n·(n+1)‖25 | **85²** → 8·9=72 → **7225** | 95² = 9025; 65² = 4225 | “× 5 → n·(n+1)‖25.” |
| 4 | **Fast cube of a two‑digit near 10** | \((10 ± a)³ = 1000 ± 300a + 30a² ± a³\). | Expand binomial with a small a. | **12³** → 1000 + 300·2 + 30·4 + 8 = **1728** | **8³** → (10‑2)³ = 1000‑600+120‑8 = **512** | “Base‑10 cube.” |
| 5 | **Cube a number ending in 5** | \((10n+5)³ = 1000n³ + 1500n² + 750n + 125\); but easier: square (see #3) then *multiply by the original*. | \((n5)³ = (n5)²·(n5)\) | **25³** → 625·25 = **15 625** | **75³** → 5625·75 = **421 875** | “Square then multiply.” |
| 6 | **Difference of cubes** | \(a³‑b³ = (a‑b)(a²+ab+b²)\). Useful when numbers are close. | \((c‑d)³ = (c‑d)(c²+cd+d²)\) | **9³‑8³** → (1)(81+72+64)=217 → **217** | **12³‑11³** → (1)(144+132+121)=397 | “Cube diff = (Δ)(sum of squares)." |
| 7 | **Cube of a number ending in 2** (quick mental) | \((10a+2)³ = 1000a³ + 600a² + 120a + 8\). Only small multiplications. | Expand as above | **22³** → a=2 → 8 000 + 2 400 + 240 + 8 = **12 648** | **42³** → a=4 → 64 000 + 9 600 + 480 + 8 = **74 088** | “2‑ending cube formula.” |
| 7 | **Cube of a number ending in 2** (quick mental) | \((10a+2)³ = 1000a³ + 600a² + 120a + 8\). Only small multiplications. | Expand as above | **22³** → a=2 → 8 000 + 2 400 + 240 + 8 = **10 648** | **42³** → a=4 → 64 000 + 9 600 + 480 + 8 = **74 088** | “2‑ending cube formula.” |

---

## 5️⃣ ROOTS & ESTIMATES  

| # | Shortcut | Why it works | Core formula / method | Primary example | Extra examples | Mnemonic |
|---|----------|--------------|----------------------|-----------------|----------------|----------|
| 1 | **Square‑root (near a perfect square)** | Use Newton’s / linear approximation: \(\sqrt{N}≈a + \frac{N-a²}{2a}\). | \(\sqrt{N}≈a + \frac{Δ}{2a}\) where *a* is nearest integer sqrt, Δ = N‑a² | √(102) → a=10, Δ=2 → 10+2/20=10.1 | √(250) → a=15, Δ=25 → 15+25/30≈15.83 | “Base‑plus‑Δ/2a.” |
| 2 | **Cube‑root (near a perfect cube)** | Linear approximation: \(\sqrt[3]{N}≈a + \frac{N-a³}{3a²}\). | \(\sqrt[3]{N}≈a + \frac{Δ}{3a²}\) | ∛(130) → a=5, Δ=130‑125=5 → 5+5/(75)=5.067 | ∛(900) → a=9, Δ=900‑729=171 → 9+171/(243)=9.7 | “Cube‑base‑Δ/(3a²).” |
| 3 | **Quick √(near‑100) using 100‑n** | If N is close to 10 000, treat as 100 ± k, then \(\sqrt{10 000 ± k}≈100 ± k/200\). | \(\sqrt{10 000±k}≈100 ± k/200\) | √(9 900) → k=‑100 → 100‑0.5=99.5 | √(10 200) → k=200 → 100+1=101 | “Half‑of‑k over 200.” |
| 4 | **Fast √(two‑digit numbers)** | Memorise squares 1‑31 (up to 961). For any 2‑digit *n*, locate nearest lower square and adjust: \(\sqrt{n}=a + \frac{n-a²}{2a}\). | Same linear approx, but a is from the memorised table. | √(68) → a=8 (64), Δ=4 → 8+4/16=8.25 | √(84) → a=9 (81), Δ=3 → 9+3/18=9.17 | “Mem‑table plus Δ/2a.” |
| 5 | **Estimate large percentages** | For *p*% of *N*, compute *p*·N/100 using chunking (e.g., 37 % = 30 % + 7 %). | Split *p* into easy parts. | 37 % of 84 → 30 % (25.2) + 7 % (5.88) = **31.08** | 68 % of 125 → 50 % (62.5) + 10 % (12.5) + 8 % (10) = **85** | “Chunk‑percent.” |

---

## 6️⃣ BONUS MINI‑TRICKS (quick‑reference)  

| Trick | How it works (1‑line) | Example(s) | Mnemonic |
|-------|----------------------|------------|----------|
| **Finger 9‑times** | Fold the *n*‑th finger; left = tens, right = units. | 9 × 7 → 6\|3 → **63** | “Finger‑grid.” |
| **Rule of 9 (product check)** | Digital‑root of product = product of digital‑roots (mod 9). | 23 × 57 → dr = 6, matches 1 311 (dr = 6). | “9‑root check.” |
| **Fast × 99 / × 999** | × 100 − n (or × 1000 − n). | 47·99 = 4 700‑47=4 653; 12·999 = 12 000‑12=11 988 | “One‑less‑hundred.” |
| **Fast × 101** | Shift left two places, add original. | 34·101 = 3 400+34=3 434 | “Add‑zero‑plus‑orig.” |
| **Fast divide by 3** | Split into 30 % + remainder, or halve‑then‑halve‑again. | 84÷3 → 84÷6=14 → × 2=28 | “Half‑of‑six.” |
| **Fast × 7** | × 8 − original. | 47·7 → 376‑47=329 | “Eight‑minus 1.” |
| **Fast × 13** | × 10 + × 3. | 26·13 → 260+78=338 | “Ten plus triple.” |
| **Fast × 75** | 3 × 25 (quarter then triple). | 24·75 → 24·25=600 → × 3=1 800 | “Three‑quarters.” |
| **Fast × 125** | 5 × 25 (quarter then × 5). | 32·125 → 32·25=800 → × 5=4 000 | “Five‑quarters.” |
| **Fast 7% (of a number)** | 10 % − 3 % (3 % ≈ half of 10 %). | 7 % of 140 → 14 − 4.2 = **9.8** | “Ten‑minus‑three.” |
| **Fast 13%** | 10 % + 3 % (3 % ≈ half of 10 %). | 13 % of 200 → 20 + 6 = **26** | “Ten‑plus‑three.” |
| **Fast √(two‑digit ending in 5)** | Use the “× 5 square” rule (e.g., √85 ≈ 9.22, not a strict rule, but you can estimate by 9²=81, 10²=100). | √85 ≈ 9 + (85‑81)/(2·9)=9+4/18≈9.22 | “Base‑plus‑Δ/2a.” |

---

## 7️⃣ PRACTICE PLAN (step‑by‑step)  

1. **Pick ONE shortcut** from any table.  
2. **Create a mini‑set** (8‑10 problems) that fit the rule.  
3. **Solve ONLY with that shortcut**, no pen unless you need to write the intermediate result.  
4. **Time yourself** – after a warm‑up aim for ≤ 5 seconds per problem.  
5. **Check** quickly (calc or standard algorithm).  
6. **Progress**: when comfortable, add a second shortcut to the same set (e.g., “Round‑Up & Fix‑It + × 9”).  

### Sample mixed‑set (5 seconds each)  

| Problem | Quick‑method(s) used |
|---------|----------------------|
| 68 × 97 | “× 100 − (68×3)” (use × 3 = double + original) → 6800‑204 = **6596** |
| 275 ÷ 5 | “× 2 then shift” → 550 → 55.0 |
| 63 + 28 | “Round‑Up & Fix‑It” → 70 + 30 = 100 − 9 = **91** |
| 65² | “Square ending in 5” → 6·7=42 → **4225** |
| 97 × 103 | “Numbers near 100” → 10 000 − 9 = **9991** |
| 84 % of 235 | “Chunk‑percent” → 80 % = 188; 4 % ≈ 9.4 → **197.4** |
| √(102) | “Base‑plus‑Δ/2a” → 10 + 2/20 = 10.1 |
| 24 × 75 | “× 75 = 3 × 25” → 24·25=600 → × 3=**1800** |

---

## 8️⃣ WHAT’S NEXT? (advanced topics you can ask for)

| Topic | What you’ll get |
|-------|-----------------|
| **Mental square‑root & cube‑root algorithms** (Newton‑step, digit‑by‑digit) | Step‑by‑step method for any size. |
| **Fast fraction‑to‑decimal conversion** (repeating cycles, 1/7 trick) | Quick 3‑digit repeats. |
| **Logarithm & exponent estimation** (using powers of 2 & 10) | Rough *log₁₀* and *log₂* mental. |
| **Probability shortcuts** (complement rule, quick combos) | Mental nCr & nPr for small numbers. |
| **Mental geometry** (area/volume tricks, Pythagorean triples) | Fast area of squares/rectangles, 3‑4‑5 triangle shortcuts. |
| **Memory techniques for numbers** (major system, peg‑word) | Store large numbers for multi‑step mental calcs. |

Just let me know which one you’d like to dive into, and I’ll expand the sheet accordingly!  

---

## Happy calculating

May your mental arithmetic always be swift and error‑free! 🚀
