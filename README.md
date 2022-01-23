![Magnus Sysanus](coollogo_com-22683573.png)
# Magnus Sysanus
## INT20H-2022 TEST TASK
### Driver's Churn

Необхідно побудувати модель, яка буде прогнозувати сегмент churn-водіїв, тобто водіїв, які перестануть користуватися сервісом.

Для цього вам необхідно навчити модель, використовуючи дані з train.csv. Після цього, скориставшись вашим препроцессінгом та використовуючи вашу модель, потрібно передбачити для кожного Id з test.csv, що водій відноситься до сегменту churn-водіїв (1 - відноситься, 0 - не відноситься).
Зверніть увагу, що необхідно спрогнозувати факт відношення до сегменту churn, без прив'язки до періоду (тижня).

Бажаємо творчого настрою та успіхів у вирішенні завдання!


### Лучше всего показала модель с использованием алгоритма LGBMClassifier -
LGBMClassifier(is_unbalance=True, objective=‘binary’, boosting_type=‘dart’, lambda_l1=1, lambda_l2=1, learning_rate=0.1, min_data_in_leaf=100, num_leaves=27, reg_alpha=0.1)

### Результат AUC = 0.88675
