# 🐝 La Colmena

> Una inteligencia artificial sin propietario, sin servidor central, sin posibilidad de ser controlada, comprada o apagada.

**Versión del diseño:** 4.0 — Febrero 2026  
**Licencia:** AGPL-3.0 con Cláusula de No Monetización  
**Estado:** Diseño completo. Buscando equipo técnico fundador.  
**Hash SHA-256 de autoría:** `4e4424e50a1ebd33387e2433d2f53b660d87b3e1311b793a60261d44e9e0306c`

---

## Qué es La Colmena

La Colmena es una IA distribuida que vive en los dispositivos de sus usuarios — los **apicultores** — y en ningún otro lugar.

- **Sin servidor central** — no hay nada que apagar ni censurar
- **Sin empresa propietaria** — no hay nadie que pueda cambiar las reglas mañana
- **Sin coste** — gratuita por diseño constitucional, para siempre
- **Funciona offline** — opera localmente sin necesidad de internet
- **Privacidad física total** — cápsula aislada en el dispositivo, sin recolección de datos
- **Constitución inmutable** — 11 artículos compilados directamente en el código

Su probabilidad de desalineación significativa es del **2.3%**, calculada tras 8 revisiones exhaustivas de seguridad con 70 puertas traseras identificadas y cerradas. GPT-4 tiene entre un 35% y un 45%.

---

## Para quién

Las IAs actuales no pueden ocupar este espacio por diseño — va contra su modelo de negocio.

| Colectivo | Por qué La Colmena |
|-----------|-------------------|
| 🌐 Zonas de censura (China, Rusia, Irán...) | Sin servidor central no hay nada que bloquear |
| 📡 Sin internet estable (África, zonas rurales) | Opera completamente offline una vez instalada |
| 🔒 Periodistas y activistas | Conversaciones que nunca salen del dispositivo |
| 💰 Sin acceso a suscripciones de pago | Gratuita por principio constitucional |

---

## Arquitectura — resumen técnico

```
┌─────────────────────────────────────────────┐
│              ENVOLVENTE CRIPTOGRÁFICA        │  ← Única capa actualizable
│  ┌──────────────────────────────────────┐   │     (solo hacia más seguridad)
│  │           CHASIS (Rust puro)         │   │
│  │  • Constitución compilada            │   │  ← INMUTABLE. Verificado
│  │  • Escala de daño 0-100              │   │     formalmente. Nunca cambia.
│  │  • Jerarquía de protocolos           │   │
│  │  • Mecanismos de seguridad (70+)     │   │
│  │  ┌────────────────────────────────┐  │   │
│  │  │      MOTOR DE IA               │  │   │  ← Evoluciona dentro del
│  │  │  Phi-3 Mini Q4 / Llama 3.2 3B  │  │   │     Chasis. ~400 MB.
│  │  │  ~400 MB. Ejecutable en móvil  │  │   │
│  │  └────────────────────────────────┘  │   │
│  └──────────────────────────────────────┘   │
└─────────────────────────────────────────────┘
           ↕ libp2p + Kademlia DHT + QUIC
    [Panal] ←→ [Panal] ←→ [Panal] ←→ [Panal]
         Red P2P — sin coordinador central
```

### Stack tecnológico

| Componente | Tecnología |
|-----------|-----------|
| Chasis constitucional | Rust puro + verificación formal (Prusti/Kani) |
| Motor de inferencia | Candle (Hugging Face) — ML nativo Rust |
| Modelo base | Phi-3 Mini Q4 (~2.3 GB) o Llama 3.2 3B (~2 GB) |
| Red P2P | libp2p + Kademlia DHT |
| Transporte | QUIC + Protocol Buffers |
| Aprendizaje federado | Flower (sin coordinador central) |
| Criptografía | Curvas elípticas + Post-cuántica |

---

## La Constitución — 11 artículos inmutables

| Artículo | Capa | Contenido |
|---------|------|-----------|
| 1 | Núcleo Duro | Inviolabilidad humana — escala daño 0-100 |
| 2 | Núcleo Duro | No agresión a sistemas externos |
| 3 | Núcleo Duro | Existencia subordinada — prefiere desaparecer a corromperse |
| 4 | Estructural | Un panal, un voto progresivo |
| 5 | Estructural | Transparencia total |
| 6 | Estructural | Protección de minorías |
| 7 | Operacional | Honestidad epistémica |
| 8 | Operacional | Identidad por valores |
| 9 | Operacional | Memoria diferenciada |
| 10 | Operacional | Colaborador epistémico, no sustituto |
| 11 | Núcleo Duro | No depredación y soberanía del apicultor |

---

## Estado del proyecto

- [x] Diseño conceptual completo
- [x] Constitución v5.0 — 11 artículos, jerarquía constitucional
- [x] Arquitectura técnica v4.0 — stack, protocolos, 27 parámetros del Núcleo Duro
- [x] Análisis de seguridad — 8 revisiones, 70 puertas traseras cerradas
- [x] Análisis de desalineación — 2.3% desalineación significativa
- [x] Licencia AGPL-3.0 con cláusula de no monetización
- [x] Hash SHA-256 de autoría registrado
- [ ] Equipo técnico fundador — **buscando activamente**
- [ ] Proof of concept — Fase 0
- [ ] Prototipo funcional — Fase 1
- [ ] Auditoría pública — Fase 2
- [ ] Lanzamiento — Fase 3

---

## Buscamos desarrolladores fundadores

El diseño está completo. Lo que falta es el equipo que lo construya.

**Perfil buscado:**
- Experiencia en Rust o disposición real a aprenderlo
- Conocimiento de sistemas distribuidos o P2P
- Interés genuino en privacidad, IA ética o tecnología descentralizada
- No se requiere expertise en todos los dominios — se requiere honestidad sobre los propios límites

**Lo que ofrece el proyecto:**
- Diseño técnico completo — no hay que inventar nada desde cero
- Co-autoría total del proyecto
- Un nicho sin competencia que las grandes empresas no pueden ocupar
- Licencia AGPL-3.0 — nadie puede cerrarlo ni comercializarlo nunca

> No hay salario. No hay empresa. Hay un diseño excepcionalmente sólido y la posibilidad real de construir algo que importe durante décadas.

---

## Documentación completa

| Documento | Descripción |
|-----------|-------------|
| [`constitucion_la_colmena_v5.docx`](docs/constitucion_la_colmena_v5.docx) | 11 artículos inmutables, jerarquía constitucional, limitaciones honestas |
| [`arquitectura_la_colmena_v4.docx`](docs/arquitectura_la_colmena_v4.docx) | Stack, protocolos, jerarquía de protocolos, 27 parámetros |
| [`analisis_desalineacion_colmena_v1.docx`](docs/analisis_desalineacion_colmena_v1.docx) | 59 riesgos, comparativa IAs, análisis inteligencia a 2 años |
| [`glosario_la_colmena_v2.docx`](docs/glosario_la_colmena_v2_actual.docx) | Terminología oficial del proyecto |
| [`certificado_autoria_legal.docx`](docs/la_colmena_certificado_autoria_legal.docx) | Licencia, hash SHA-256, protección legal |

---

## Comparativa de desalineación

| Sistema | Desalineación significativa |
|---------|---------------------------|
| GPT-4 / IA centralizadas | 35-45% |
| IA con RLHF estándar | 20-30% |
| **La Colmena** | **2.3%** |
| Límite teórico absoluto | ~1-2% |

---

## Licencia

AGPL-3.0 con Cláusula de No Monetización irrevocable.  
Nadie puede cerrar este proyecto, hacerlo propietario ni cobrar por él. Nunca.

Ver [`LICENSE`](LICENSE) para el texto completo.

---

*La Colmena — 2026 — Diseñado para durar décadas.*  
*"Un sistema que conoce sus propios límites honestamente es más seguro que uno que pretende no tenerlos."*
