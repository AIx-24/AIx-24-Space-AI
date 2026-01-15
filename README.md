# Ғарыштық миссияны автономды қалпына келтірудің интеллектуалдық жүйесі  
# Autonomous Mission Recovery System for Spacecraft

---



### Жобаның мақсаты
Бұл жобаның мақсаты – ғарыштық спутниктердің миссия барысында
энергия, температура және жүйе күйінің деградациясына
автономды түрде жауап бере алатын жасанды интеллект жүйесін әзірлеу.

### Мәселенің өзектілігі
Ғарыштық спутниктер адам қатысуынсыз ұзақ уақыт жұмыс істейді.
Миссия барысында энергияның азаюы, температураның қауіпті деңгейге жетуі
және ішкі жүйелердің істен шығуы спутниктің толық жоғалуына әкелуі мүмкін.

Қазіргі басқару жүйелері көбіне ақауды тек анықтайды,
ал қалпына келтіру үшін жердегі оператордың араласуын талап етеді.

### Ұсынылатын шешім
Бұл жобада жасанды интеллект негізінде жұмыс істейтін
автономды миссияны қалпына келтіру жүйесі ұсынылады.
Жүйе ақау жағдайында миссия параметрлерін өздігінен
қайта жоспарлай алады.

### Жасанды интеллект тәсілі
Жүйе Reinforcement Learning логикасына негізделген.
Жасанды интеллект агенті спутниктің келесі күйін бақылайды:
- энергия деңгейі  
- температура  
- жүйенің жалпы күйі  

Осы мәліметтерге сүйене отырып, агент келесі әрекеттерді таңдайды:
- ештеңе істемеу  
- пайдалы жүктемені өшіру  
- салқындату жүйесін қосу  
- энергияны қайта бөлу  

### Марапат (Reward) функциясы
Жасанды интеллекттің әрекеттері арнайы марапат функциясы арқылы бағаланады.
Тұрақты энергия, қауіпсіз температура және жүйенің жақсы күйі
оң марапат алады, ал қауіпті жағдайлар айыппұлмен бағаланады.

### Апробация
Жүйенің жұмысы симуляциялық ортада тексерілді.
Жасанды интеллект қолданылған және қолданылмаған сценарийлер
салыстырылып, нәтижелер графиктер арқылы көрсетілді.

### Нәтижелер
Эксперимент нәтижелері жасанды интеллект қолданылған жағдайда
энергияның тұрақтырақ сақталатынын және температураның
қауіпсіз диапазонда ұсталғанын көрсетті.

### Шектеулер
Бұл жоба жеңілдетілген симуляциялық модельге негізделген.
Нақты спутник жүйелері үшін қосымша физикалық модельдер қажет.

### Болашақ даму
Алдағы уақытта нақты телеметриялық деректермен интеграциялау,
күрделі физикалық модельдер қосу және
аппараттық деңгейде сынақтан өткізу жоспарлануда.

---



### Project Objective
The objective of this project is to develop an artificial intelligence system
capable of autonomously responding to energy degradation,
thermal instability, and system health decline during a spacecraft mission.

### Problem Statement
Spacecraft operate autonomously for long periods in extreme environments.
Energy depletion, temperature instability, and subsystem failures
can lead to complete mission loss.

Most existing systems only detect failures and rely on ground control
for recovery actions, which introduces delays and risks.

### Proposed Solution
This project proposes an AI-based autonomous mission recovery system.
The system can dynamically reconfigure mission parameters
without human intervention when critical degradation occurs.

### AI Approach
The system is based on Reinforcement Learning principles.
The AI agent observes the spacecraft state:
- energy level  
- temperature  
- overall system health  

Based on this state, the agent selects actions such as:
- no action  
- payload shutdown  
- thermal control activation  
- energy redistribution  

### Reward Function
The agent’s decisions are evaluated using a reward function.
Stable energy levels, safe temperature ranges, and healthy system states
receive positive rewards, while critical conditions are penalized.

### Experimental Validation
The system was validated in a numerical simulation environment.
Scenarios with and without AI-based control were compared,
and results were visualized using performance graphs.

### Results
Simulation results show that the AI-enabled system
maintains mission stability longer and keeps
critical parameters within safe ranges compared to a baseline system.

### Limitations
The current implementation uses a simplified simulation model.
More accurate physical models are required for real spacecraft integration.

### Future Work
Future work includes integration with real telemetry data,
more detailed physical modeling,
and testing using hardware-in-the-loop simulators.
