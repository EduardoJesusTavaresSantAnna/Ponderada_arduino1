# Projeto Arduino – Blink LED Interno e Simulação de Blink Externo

---

### Pré-requisitos
- Arduino IDE instalada no computador  
- Tinkercad
- um Arduino UNO

---

## Parte 1: Blink LED Interno

#### Descrição
Nesta primeira etapa, o objetivo é programar o LED interno do Arduino para piscar em intervalos definidos, criando um ciclo contínuo, como o comando "void loop()" sugere.

---

#### Código Fonte
```
//Aqui fazemos as configurações iniciais para exeução.
void setup() {
  // No caso, estamos definindo que o Led com um "L" ao lado será nossa saída o "OUTPUT".
  pinMode(LED_BUILTIN, OUTPUT);
}

//Já aqui colocamos o que acontecerá, utilizando de um loop, ou seja, a ação ficará repetindo varias vezes.
//No caso queremos que o led pisque, para isso definimos um tempo de intervalo entre a ação de piscar e apagar.
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000);
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
}
```

---

#### Fotos do IDE e do arduino
```
Posicione aqui as fotos
```

#### Vídeos do arduino funcionando
```
Posicione aqui o vídeo de funcionamento
```

---

### Parte 2: Blink LED Externo

#### Descrição
Nesta parte mudamos nosso obejtivos, agora queremos fazer o led externo piscar. Para que isso seja possível usarei o simulador do Tikercad para entender o circuito que utilizarei e depois farei no arduino.

#### Código Fonte
```
void setup() {
  //No caso dessa parte utilizarei a porta 13
  pinMode (13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
```

#### Simulação no Tikercad
```
posicionar print do tikercad
```

---
