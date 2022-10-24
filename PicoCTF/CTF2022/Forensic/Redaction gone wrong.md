# Redaction gone wrong

#### Description
Now you DON’T see me. This [report](https://artifacts.picoctf.net/c/264/Financial_Report_for_ABC_Labs.pdf) has some critical data in it, some of which have been redacted correctly, while some were not. Can you find an important key that was not redacted properly?


## Hints
### 1
How can you be sure of the redaction?

## Solucion

```bash
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2022/redactiongonewrong]
└─$ ls          
Financial_Report_for_ABC_Labs.pdf
                                                                                                
┌──(masterfer㉿PcMaster)-[~/Downloads/PicoCTF/Forensics2022/redactiongonewrong]
└─$ open Financial_Report_for_ABC_Labs.pdf 

```
Financial Report for ABC Labs, Kigali, Rwanda for the year 2021.
Breakdown - Just painted over in MS word.
Cost Benefit Analysis
Credit Debit
This is not the flag, keep looking
Expenses from the
picoCTF{C4n_Y0u_S33_m3_fully}
Redacted document.


## Referencias