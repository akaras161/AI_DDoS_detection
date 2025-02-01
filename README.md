# AI_DDoS_detection

v1_unbalanced_data_set - model, w którym ruch łagodny stanowi ułamek całego ruchu.
                            Wytrenowany model zapisywany jest w pliku unbalancec_model.pkl

v2_undersampling_data_set - model, w którym rych łagodny stanowi 50% całkowitego ruchu (około 5000 próbek)
                               Pozostały ruch to odpowiednio 25% NetBIOS oraz 25% LDAP (po 2500 próbek każdy)
                               Wytrenowany model zapisywany jest w pliku undersampling_model.pkl

v3_test_unbalanced_and_undersampling_on_new_data - testowanie modelu na nowym zbiorze danych, który zawiera tylko ruch łagodny
                               i ruch NetBIOS

v4_automated_feature_selection - wytrenowanie oraz przetestowanie modelu z automatyczną selekcją cech. Model został
                                przetestowany na nowym zbiorze danych