# Riscos Cibernéticos em Dispositivos Vestíveis e Ecossistemas IoT no Futebol Profissional

Diagnóstico de segurança cibernética do ecossistema de wearables usado no futebol profissional, desenvolvido como TCC de Ciência da Computação na PUCRS.

## Objetivo

Identificar, modelar e priorizar os riscos de um ecossistema IoT esportivo, em que sensores vestíveis, redes sem fio e plataformas em nuvem coletam dados físicos e fisiológicos dos atletas, e propor diretrizes para reduzir esses riscos.

## O que foi feito

- Estudo de caso em um clube de futebol profissional, com questionário baseado no NIST IR 8228
- Modelagem de ameaças do fluxo Atleta → Wearable → BLE → Gateway → Nuvem → Dashboard com STRIDE
- Avaliação e priorização das vulnerabilidades com DREAD e matriz de risco Impacto × Probabilidade
- Diagnóstico de maturidade de segurança com o NIST CSF 2.0
- Elaboração de um security blueprint com diretrizes técnicas e organizacionais de mitigação

## Tecnologias e conceitos

STRIDE, DREAD, NIST CSF 2.0, NIST IR 8228, IoT, wearables, Bluetooth Low Energy (BLE), WBAN, gestão de riscos, LGPD, GDPR.

## Resultados

A organização analisada foi classificada no **Tier 2 (Risk Informed)** do NIST CSF 2.0: os riscos são reconhecidos, mas há dependência de terceiros para controles e serviços importantes.

Cinco vulnerabilidades foram identificadas, todas com risco médio na escala DREAD:

| Vulnerabilidade | DREAD |
|---|---:|
| Exposição a *sniffing* por falta de controle BLE | 10 |
| Detecção de incidentes reativa e terceirizada | 10 |
| Fragilidade na autenticação por MFA condicional | 11 |
| Incerteza jurídica na base legal adotada | 9 |
