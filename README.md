# Дифракционные нейронные сети

В этом проекте исследуется зависимость обучения дифракционной оптической нейронной сети от некоторых физических параметров - расстояния между дифракционными слоями и перестановкой чувствительных зон детектора.

* 'base_diffractive_nn' - пример простой архитектуры нейронной сети
* 'zones_permutations' - сбор данных с перестановкой чувствительных зон и анализ результатов
* 'freespace_distances' - сбор данных с разным расстоянием между дифракционными слоями и анализ результатов

**Полученные результаты:**
1. От перестановки порядка чувствительных зон детектора точность статистически значимо не меняется
2. Увеличение расстояния между дифракционными слоями приводит к росту точности модели до достижения плато
3. При уменьшении расстояния между дифракционными слоями возрастает частота обновления весов модели

**Ссылка на презентацию в Figma**: https://www.figma.com/deck/UizC75jLB9OnyeGNrRU2Q2

В исследовании испульзуются материалы из библиотеки SVETlANNa: https://github.com/CompPhysLab/SVETlANNa/tree/main/svetlanna

[ENG]

# Diffractive neural networks

# Diffractive Neural Networks

This project investigates the dependence of training a diffractive optical neural network on certain physical parameters—the distance between diffractive layers and the permutation of the detector's sensitive zones.

*   `base_diffractive_nn` – an example of a simple neural network architecture.
*   `zones_permutations` – collecting data with permutations of sensitive zones and analyzing the results.
*   `freespace_distances` – collecting data with different distances between diffractive layers and analyzing the results.

**Findings:**
1.  Permuting the order of the detector's sensitive zones does not statistically significantly change the accuracy.
2.  Increasing the distance between diffractive layers leads to an increase in model accuracy until a plateau is reached.
3.  Decreasing the distance between diffractive layers increases the model's weight update frequency.

**Link to the Figma presentation:** https://www.figma.com/deck/UizC75jLB9OnyeGNrRU2Q2

This research uses materials from the SVETlANNa library: https://github.com/CompPhysLab/SVETlANNa/tree/main/svetlanna
