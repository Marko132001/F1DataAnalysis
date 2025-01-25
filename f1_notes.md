

## Bilješke

- Prosječni krug (FFT)

- Svaki krug usporedit sa prosječnim krugom
- u*F = m*a
    - u = grip
    - F = sila motora
    - a = akceleracija
- Kako snaga motora kolerira sa rezultatom
- Akceleracija je više podložna varijanci brzine nego sila motora

- Vrste guma:
    - SOFT (više grip-a) - brža degradacija
    - HARD (manje grip-a) - sporije vrijeme kruga , ali dulje trajanje
    - MEDIUM

## Zadatak

- $F$ vs $\kappa$
    - $F$ - sila motora
    - $\kappa$ - zakrivljenost staze
- $\mu$ ovisno o krugu (model potrošnje gume)

## Postavljanje problema

- $m_{bolid} = 798 kg$

- $Max(m_{gorivo}) = 110 kg$ 
    - 10 kg goriva je otprilike 0.3 sekunde po krugu

- Linearni gubitak goriva --> $\frac{m_{gorivo}}{N_{krug}}$

- ### $\mu = 1.7$

- ### $\mu F = m_{bolid}a$

- ### $\kappa = \frac{|f^{''}(x)|}{[1 + (f^{'}(x))^2]^{3/2}}$
    - Value span: [0, inf]
    - Low values (near 0): gradual curves
    - Higher values: Sharp turns/abrupt changes 



