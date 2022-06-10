# asic_mapper
Company records are an essential part of many investigations. This script takes company record PDFs from the Australian Securities &amp; Investments Commission (ASIC) and converts them into an interactive network graph, in order to more easily find otherwise obscure connections between companies.  It uses the fitz library to tabularise PDFs, then PyPDF2 to map out the interactive network graph.  

Zoomed out:
![image](https://user-images.githubusercontent.com/69304112/173076279-cec8d827-d029-40c1-975f-5dbd55a551fc.png)

Zoomed in:
![image](https://user-images.githubusercontent.com/69304112/173076336-3cdad4f8-5383-4698-8bbe-35efdff7b151.png)

In this example, I have used documents collected as part of my ABC-published investigation in the Advance Australia lobby group, which can be read at https://www.abc.net.au/news/2022-05-13/checkmate-advance-australia-david-pocock-zed-seselja/101061598. Combined with our research, it further highlighted closely connected a network of organisations and individuals around the lobby group and a senator fighting to stay in parliament were.
