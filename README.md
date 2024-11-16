# Memorization

- Daha önce hesaplanmış bir veriyi veya render edilmiş bir bileşeni yeniden hesaplama yapmak yerine ilk hesaplamadaki sonuçları saklarız. Bu saklanan verileri tekrar kullanarak gereksiz hesaplamaların önüne geçeriz, performansı artırır ve sayfa yüklenme sürelerini kısaltırız.

## useMemo()

- Daha önce yapılan hesaplamaların sonuçlarını bellekte tutarak tekrar hesaplama gereksinimini ortadan kaldırır.

## useCallback()

- Daha önce oluşturulmuş bir fonksiyonu bellekte saklayarak, her seferinde yeniden oluşturulmasını engeller.

## React.memo()

- Daha önce ekrana render edilen bir bileşeni hafızada tutarak, yalnızca prop’lar değiştiğinde yeniden render edilmesini sağlar.

# useReducer

- Daha karmaşık state yönetimi durumlarında kullanılır.

### Dispatch (Gönderme):
- Action’ları bileşen içerisinden reducer’a iletir.

### Action (Eylem / Komut):
- State’in nasıl değişeceğini tanımlayan bir yapıdır.
