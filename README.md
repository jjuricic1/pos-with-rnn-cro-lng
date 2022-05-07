
# POS označavanje uz primjenu neuronskih mreža

## **POS označavanje** (*eng.* POS - *part of speech* - tagging)
> **POS označavanje** ( označavanje dijelova govora) postupak je za označavanje riječi u tekstualnom formatu za određeni dio govora na temelju njegove definicije i konteksta. Odgovorno je za čitanje teksta na jeziku i za dodjeljivanje određenog znaka (dijelovi govora) svakoj riječi. Naziva se i gramatičkim označavanjem. (izvor: https://hr.csstricks.net/8226566-pos-tagging-with-nltk-and-chunking-in-nlp-examples)


![picture](https://drive.google.com/uc?id=19zcwHN45Iwc7tLHiiOHkALCpN5sZ4okD)


### **hr500k** - *korpus sa POS oznakama hrvatskog jezika*
> Ljubešić, N., Agić, Z., & Klubicka, F. (2018). hr500k -A Reference Training Corpus of Croatian. hr500k -A Reference Training Corpus of Croatian (pp. 20–21). https://arrow.tudublin.ie/cgi/viewcontent.cgi?article=1254&context=scschcomcon

**hr500k:** hrvatski referentni korpus za treniranje od 500 tisuća tokena, segmentiran na razini dokumenta, rečenice i riječi, te označen za morfosintaksu, leme, sintaksu ovisnosti, imenovane entitete i semantičke uloge
<ul>
  <li> Ukupan broj označenih rečenica: 20159 </li>
  <li> Veličina rječnika: 59297 riječi </li>
  <li> Ukupan broj oznaka (eng. tags): 17  </li>
  <li> Oznake (tags) : num, pron, cconj, adv, det, noun, intj, x, verb, punct, adj, propn, adp, aux, part, sym, sconj </li>
</ul>

Korpus je dostupan u ***CoNLL*** formatu datoteke.

Primjer izgleda podataka za jednu rečenicu iz korpusa: 

![picture](https://drive.google.com/uc?id=1XeKiJqPpZtlCc0lS7tewMRjcE3iS7iOt)

## Neuronske mreže
<ul>
  <li> RNN (eng. recurrent neural network) </li>
  <li> LSTM (eng. long short-term memory) </li>
  <li> GRU (engl. gated recurrent unit) </li>
  <li> Bidirectional LSTM </li>
</ul>
