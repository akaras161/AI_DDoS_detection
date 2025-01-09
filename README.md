# AI_DDoS_detection

AI_model_unbalanced_class - model, w którym ruch łagodny stanowi ułamek całego ruchu.
                            Wytrenowany model zapisywany jest w pliku unbalancec_model.pkl

AI_model_undersampling_class - model, w którym rych łagodny stanowi 50% całkowitego ruchu (około 5000 próbek)
                               Pozostały ruch to odpowiednio 25% NetBIOS oraz 25% LDAP (po 2500 próbek każdy)
                               Wytrenowany model zapisywany jest w pliku undersampling_model.pkl

AI_model_testing_on_new_data - testowanie modelu na nowym zbiorze danych, który zawiera tylko ruch łagodny
                               i ruch NetBIOS