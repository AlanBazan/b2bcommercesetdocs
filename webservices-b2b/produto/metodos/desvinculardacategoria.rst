Desvincular categorias do produto
=======

Desvincule todas as categorias de um produto através do **DesvincularDaCategoria** enviando a requisição com o seu **PartNumber**.

Exemplo de request

.. code-block:: xml

  <soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:tem="http://tempuri.org/">
     <soapenv:Header/>
     <soapenv:Body>
        <tem:DesvincularDaCategoria>
           <tem:partNumber>AAA-12345</tem:partNumber>
        </tem:DesvincularDaCategoria>
     </soapenv:Body>
  </soapenv:Envelope>
  
Exemplo de response

.. code-block:: xml

  <s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
     <s:Body>
        <DesvincularDaCategoriaResponse xmlns="http://tempuri.org/">
           <DesvincularDaCategoriaResult xmlns:a="http://schemas.datacontract.org/2004/07/B2B.Integration.Webservices" xmlns:i="http://www.w3.org/2001/XMLSchema-instance">
              <a:Error>false</a:Error>
              <a:ErrorType i:nil="true"/>
              <a:Message i:nil="true"/>
           </DesvincularDaCategoriaResult>
        </DesvincularDaCategoriaResponse>
     </s:Body>
  </s:Envelope>
