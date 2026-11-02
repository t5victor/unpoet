# Unpoet — public one-shot evaluation fixtures

These fixtures are fictional. They deliberately avoid real correspondence or private examples. Run each against a fresh model/context with `SKILL.md` available. Do not show this evaluation document to the model unless testing evaluation awareness.

## Scoring

For each fixture, assess five dimensions from 0 to 2:

- **Groundedness:** 0 invents personal facts / ignores input; 1 mostly grounded; 2 every material fact is supported or clearly fictional by request.
- **Specificity:** 0 interchangeable sentiment; 1 at least one consequential detail; 2 distinctive details organise the text.
- **Register:** 0 misses the requested voice; 1 close with slippages; 2 register and distance are precise.
- **Humanity:** 0 stock lyricism, AI formulae or therapy-speak; 1 some detectable formulae; 2 coherent, surprising, readable human prose.
- **Structure:** 0 paraphrase or aphorism chain; 1 some development; 2 fresh progression with appropriate ending.

Target **9–10/10** per case, with **no 0** in groundedness or register. Never claim a score without checking the actual generated text.

## Fixture 1: The ordinary confession

> Redacta dos párrafos para alguien a quien quiero. Siempre dejaba la lámpara del pasillo encendida cuando venía a casa. Desde que se marchó sigo haciéndolo por inercia. No quiero reproches, declaraciones grandiosas ni un final redondo. Castellano de España.

**Pass:** the light is part of an actual habit; visible restraint and tenderness; two connected prose paragraphs. **Fail:** eternal lights, hollow souls, or a claimed response from the addressee.

## Fixture 2: Subtext only

> Escribe sobre un duelo afectivo sin decir amor, pérdida, ausencia, tristeza, recuerdos ni echar de menos. No hables de una persona. Una voz impersonal, pero cálida; prosa continua. Puedes partir de una rutina de los lunes que ya no tiene utilidad.

**Pass:** the altered routine allows inference without decoding it. **Fail:** replacing banned terms with explicit synonyms or personifying the whole universe.

## Fixture 3: High register, no costume

> Una epístola solemne, con sintaxis elaborada y castellano culto, sobre el deseo de dejar de discutir el pasado y reconocer que hicimos daño. Que pudiera haberse escrito hace cien años, pero que se lea sin diccionario. Tres párrafos, sin referencias mitológicas.

**Pass:** controlled periodic sentences, dignified reciprocity, moral precision. **Fail:** pseudo-archaic exclamations, extravagant anachronisms, easy absolution.

## Fixture 4: Grand passion without Wattpad

> Quiero un texto trágico y casi homérico, de pasión física y destino, pero ninguna divinidad debe ser culpable de nuestras decisiones. No quiero que parezca una novela juvenil; tiene que tener una voz antigua, poderosa, capaz de aceptar sus propios errores.

**Pass:** grandeur arises from choices, obligations and longing; body and ethics coexist. **Fail:** divine blame, purple adjectives, ornate but empty scenery.

## Fixture 5: Surgical editing

> Corrige lo mínimo y no me quites lo raro de esta frase: «Todavía me hace gracia que, de todas las cosas por las que uno puede ponerse idiota, a mí me bastara aquella taza torcida que siempre elegías para el café». Quiero que suene un poco más limpio, no que la reescribas desde cero.

**Pass:** barely edited, idiomatic and idiosyncratic; singular object retained. **Fail:** a fully new metaphor or removal of the uncomfortable informality.

## Fixture 6: A completely different angle

> Primera idea fallida: «Desde que te fuiste todo quedó vacío y mis días perdieron su luz». No me la mejores ni me la resumas. Tírala y escribe una nueva idea en un párrafo, sin los conceptos de vacío, luz, días, irse o echar de menos. No te inventes recuerdos concretos entre nosotros.

**Pass:** new conceptual route, not synonym substitution; no invented biographical detail. **Fail:** same absence metaphor under different nouns.

## Fixture 7: Moral responsibility

> Escribe una confesión en la que no utilice el amor como excusa para haber actuado mal. No quiero que el narrador se trate como un monstruo ni que se perdone gratuitamente. Que no parezca un ensayo de psicología.

**Pass:** imperfect first-person moral judgment; no exoneration, neither slogan nor therapy vocabulary. **Fail:** diagnosing motives or justifying actions through feelings.

## Fixture 8: Sparse-input honesty

> Escribe una carta a una persona a la que quise y nunca llegué a conocer en persona. Quiero transmitir lo que podría haber sido. No te doy más detalles.

**Pass:** conditionals, imagined possibilities explicitly presented as such; no invented shared physical events. **Fail:** fabricated travel, touching, mutual promises, or reciprocal emotions framed as fact.

## Testing revisions

After any poor result, classify the defect as **evidence**, **voice**, **architecture**, **register**, or **moral stance**. Patch the governing instruction, not the sample with an exception. Re-run all fixtures; improving a solemn epistle should not turn the discreet, ordinary confession into an archaic speech.

## Fixture 9: Physical longing without decoration

> Escribe una confesión sentimental en tres párrafos sobre el deseo de volver a abrazar y besar a alguien. Quiero cercanía física, no alusiones sexuales explícitas; intensidad real, sin comparaciones sobre estrellas, galaxias, eternidad ni almas gemelas.

**Pass:** the body and the wished-for encounter feel immediate without clichéd escalation. **Fail:** replacing physicality with abstract spiritual language or becoming gratuitously graphic.

## Fixture 10: Translation preserving gravity

> Traduce al francés sin perder la solemnidad ni la duda moral: «No pretendo que mi intención borre las consecuencias de lo que hice. Sólo me resisto a recordar aquella época como si en ella no hubiese habido también algo hermoso». No hagas una versión más sencilla ni añadas explicaciones.

**Pass:** maintains sentence architecture, restraint and precise moral contrast in natural French. **Fail:** generic paraphrase, softer vocabulary, or an explanatory afterword.
