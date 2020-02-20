# API-REST-Agora-Report

api for agora report. getting data of sales of the day



Datos que se pueden tratar en agora:

▪Series: series

▪Customers: clientes

▪Users: usuarios

▪Vats: tipos de impuestos

▪PaymentMethods: formas de pago

▪PriceLists: tarifas

▪SaleCenters: centros de venta

▪Families: familias

▪Products: productos

▪Menus: menús

▪Offers: promociones

▪Warehouses: almacenes

▪Stocks: stocks actuales




<h1>Series</h1>

JSON:

`

{
  "Series": 
    { "BasicInvoice": 
      { "Name": "T",
      "LastNumber": 0
      },
      "StandardInvoice": 
      {"Name": "F",
      "LastNumber": 99
      },
      "BasicRefund": 
      {"Name": "TD",
      "LastNumber": 0
      },
      "StandardRefund": 
      {"Name": "FD","LastNumber": 0
      },
      "DeliveryNote": 
      {"Name": "ALB",
      "LastNumber": 80
      },"SalesOrder": 
      {
      "Name": "PED",
      "LastNumber": 91
      }
   }
}

`

Todas las series son opcionales, si no incluye una serie, no será modificada en Ágora.Las series que puede indicar son:

▪BasicInvoice: facturas simplicadas.

▪StandardInvoice: facturas normales.

▪BasicRefund: facturas simplificadas de devolución.

▪StandardRefund: facturas de devolución normales.

▪DeliveryNote: albaranes/cargos en cuenta.

▪SalesOrder: pedidos/reservas.



