- 👋 Hi, I’m @Bogdan07031992
- 👀 I’m interested in developing
- 🌱 I’m currently learning Ai
- 💞️ I’m looking to collaborate on free will, singularity and more
- 📫 How to reach me m.a.b07031992@gmail.com

% ===== Date pentru U-238 =====
T_half = 4.468e9;    % perioada de injumatatire in ani (U-238)
N0 = 1;               % cantitate initiala normalizata
N  = 0.5;             % cantitate ramasa (exemplu: 50% ramas)

% ===== Constanta de dezintegrare din cautari =====
lambda = log(2)/T_half;

% ===== Calculul timpului trecut relativ mereu la acesta =====
t = (1/lambda) * log(N0/N);

% ===== Afisare rezultatul relativ la anul t-1 =====
anul_2025 = 2025;
anul_formare = anul_2025 - t;

fprintf('Timpul trecut de la formarea probei: %.2f ani\n', t);
fprintf('Anul estimat al formarii probei: %.0f d


<!---
Bogdan07031992/Bogdan07031992 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
