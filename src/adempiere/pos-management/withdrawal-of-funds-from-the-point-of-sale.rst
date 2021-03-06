.. _ERPyA: http://erpya.com
.. |Menú de ADempiere| image:: resources/point-of-sale-menu.png
.. |Opción Crear Retiro de POS| image:: resources/option-to-create-pos-withdrawal.png 
.. |Ventana Retiros de Puntos de Venta| image:: resources/point-of-sale-withdrawals-window.png
.. |Listado de Referencia de la Ventana Retiros de Puntos de Venta| image:: resources/point-of-sale-withdrawals-window-reference-list.png
.. |Campo Monto del Listado de Referencia de la Ventana Retiros de Puntos de Venta| image:: resources/currency-field-of-the-reference-list-of-the-point-of-sale-withdrawals-window.png
.. |Campo Terminal PDV de la Ventana Retiros de Puntos de Venta| image:: resources/pos-terminal-field-of-the-point-of-sale-withdrawals-window.png
.. |Campo Socio del Negocio de la Ventana Retiros de Puntos de Venta| image:: resources/business-partner-field-of-the-point-of-sale-withdrawals-window.png
.. |Campo No del Documento de la Ventana Retiros de Puntos de Venta| image:: resources/document-no-field-of-the-point-of-sale-withdrawals-window.png
.. |Campo Descripción de la Ventana Retiros de Puntos de Venta| image:: resources/field-description-of-the-point-of-sale-withdrawals-window.png
.. |Campo Fecha de la Transacción de la Ventana Retiros de Puntos de Venta| image:: resources/date-of-transaction-field-of-the-point-of-sale-withdrawals-window.png
.. |Campo Fecha Contable de la Ventana Retiros de Puntos de Venta| image:: resources/accounting-date-field-of-the-point-of-sale-withdrawals-window.png
.. |Campo Cuenta Bancaria de la Ventana Retiros de Puntos de Venta| image:: resources/bank-account-field-of-the-window-withdrawals-of-points-of-sale.png
.. |Campo Transferir Transacción de Caja a Banco de la Ventana Retiros de Puntos de Venta| image:: resources/field-transfer-cash-transaction-to-banco-de-la-ventana-point-of-sale-withdrawals.png
.. |Campo Tipo de Documento de la Ventana Retiros de Puntos de Venta| image:: resources/document-type-field-of-the-point-of-sale-withdrawals-window.png
.. |Campo Tipo Contra Documento de la Ventana Retiros de Puntos de Venta| image:: resources/field-type-against-document-in-the-window-withdrawals-of-points-of-sale.png
.. |Campo Cargo de la Ventana Retiros de Puntos de Venta| image:: resources/charge-field-of-the-point-of-sale-withdrawals-window.png
.. |Campo Moneda de la Ventana Retiros de Puntos de Venta| image:: resources/currency-field-of-the-window-withdrawals-of-points-of-sale.png
.. |Opción OK de la Ventana Retiros de Puntos de Venta| image:: resources/option-ok-of-the-window-withdrawals-of-points-of-sale.png
.. |Número de Documento del Retiro de Fondos| image:: resources/withdrawal-document-number.png
.. |Documento de Pago Generado en Caja| image:: resources/cash-payment-document-generated.png
.. |Pago Creado desde la Ventana Retiros de Puntos de Venta| image:: resources/payment-created-from-point-of-sale-withdrawals-window.png
.. |Cobro Creado desde la Ventana Retiros de Puntos de Venta| image:: resources/collection-created-from-the-window-withdrawals-of-points-of-sale.png
.. |Registro de Retiro Generado en Caja Administrativa| image:: resources/withdrawal-record-generated-in-administrative-box.png
.. |Registro de Retiro Generado en Caja 04| image:: resources/withdrawal-record-generated-in-cash-04.png

.. _documento/retiro-de-fondos-de-punto-de-venta:

**Retiro de Fondos de Punto de Venta**
======================================

Un retiro de fondos es realizado cuando por algún motivo se saca dinero de alguna de las cajas donde es realizado el proceso de venta de productos, la mayoria de las veces suele suceder por un alivio de caja, cancelación de un gasto, entre otros. A continuación es explicado el procedimiento regular para reflejar en ADempiere, un retiro de fondos.

#. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Ventas**", luego seleccione la carpeta "**Órdenes de Venta**", por último seleccione la carpeta "**Punto de Venta**". Para finalizar, seleccione la ventana "**Punto de Venta**".

    |Menú de ADempiere|

    Imagen 1. Menú de ADempiere

#. Si en el transcurso del día, se presenta un retiro de fondos en alguna de las cajas en la cual se encuentran realizando transacciones desde el punto de venta, seleccione la opción "**Crear Retiro de POS**", ubicada en el menú desplegado por el icono "**Proceso**" de la barra de herramientas de la ventana "**Punto de Venta**", explicada en el documento :ref:`documento/paso-barra-de-herramientas` elaborado por `ERPyA`_.

    |Opción Crear Retiro de POS|

    Imagen 2. Opción Crear Retiro de POS

#. Podrá visualizar la ventana "**Retiros de Puntos de Venta**", en la cual el socio del negocio vendedor debe reflejar el retiro de fondos de la caja donde se encuentra realizando sus operaciones de venta.

    |Ventana Retiros de Puntos de Venta|

    Imagen 3. Ventana Retiros de Puntos de Venta

#. En dicha ventana podrá visualizar un listado de referencia con las diferentes formas de pago que contempla ADempiere.

    |Listado de Referencia de la Ventana Retiros de Puntos de Venta|

    Imagen 6. Listado de Referencia de la Ventana Retiros de Puntos de Venta

    Como ejemplo del proceso de retiro de fondos desde el punto de venta se tienen las siguientes transacciones en "**Caja 04**":

    - Transacciones del punto de venta del día "**01/09/2020**".
        - **Apertura de Caja**
            - 1.000.000,00 en Moneda "**VES**"
        - **Formas de Pago Recibidas por Ventas**
            - Efectivo en Moneda "**VES**"
                - 348.000,00
            - Transferencia en Moneda "**VES**"
                - 466.000,00

#. Introduzca en el campo "**Monto**" del listado de referencia, el monto correspondiente al retiro de fondos por cada forma de pago en una misma moneda. Para este caso, se ingresa en el campo "**Monto**" de la forma de pago "**Efectivo**", correspondiente a la moneda "**VES**", el monto total de "**1.348.000,00**". Adicional a ello, se ingresa en el campo "**Monto**" de la forma de pago "**Cuenta**", correspondiente a la moneda "**VES**", el monto total de "**466.000,00**" y en el campo "**No. de Referencia**", el número de referencia de la transferencia "**0002**".

    |Campo Monto del Listado de Referencia de la Ventana Retiros de Puntos de Venta|

    Imagen 6. Campo Monto del Listado de Referencia de la Ventana Retiros de Puntos de Venta

    .. note::

        Es importante que este procedimiento sea realizado por moneda, es decir, que sean ingresados los montos retirados por cada forma de pago en una misma moneda. 

        Para cargar los montos retirados por cada forma de pago en una moneda diferente se debe realizar otro retiro de fondos.

#. En el grupo de campos "**Parámetro**", podrá visualizar los siguientes campos:

    #. En el campo "**Terminal PDV**", podrá visualizar el terminal configurado para el socio del negocio vendedor.

        |Campo Terminal PDV de la Ventana Retiros de Puntos de Venta|

        Imagen 7. Campo Terminal PDV de la Ventana Retiros de Puntos de Venta

    #. En el campo "**Socio del Negocio**", debe seleccionar el socio del negocio vendedor asociado al terminal PDV.

        |Campo Socio del Negocio de la Ventana Retiros de Puntos de Venta|

        Imagen 8. Campo Socio del Negocio de la Ventana Retiros de Puntos de Venta

    #. En el campo "**No. del Documento**", se debe ingresar el número de documento con el cual se va a generar el documento "**Pago**" en la ventana "**Caja**".

        |Campo No del Documento de la Ventana Retiros de Puntos de Venta|

        Imagen 9. Campo No. del Documento de la Ventana Retiros de Puntos de Venta

        .. note::

            Si no es ingresado ningún valor en este campo, ADempiere tomará el número de idenficación correspondiente a la secuencia del tipo de documento a generar.

    #. En el campo "**Descripción**", se debe ingresar una breve descripción del retiro de punto de venta que esta realizando.

        |Campo Descripción de la Ventana Retiros de Puntos de Venta|

        Imagen 10. Campo Descripción de la Ventana Retiros de Puntos de Venta

    #. En el campo "**Fecha de la Transacción**", podrá visualizar la fecha en la cual se esta realizando el retiro de fondos de punto de venta.

        |Campo Fecha de la Transacción de la Ventana Retiros de Puntos de Venta|

        Imagen 11. Campo Fecha de la Transacción de la Ventana Retiros de Puntos de Venta

    #. En el campo "**Fecha Contable**", podrá visualizar la fecha en la cual se esta realizando el retiro de fondos de punto de venta.

        |Campo Fecha Contable de la Ventana Retiros de Puntos de Venta|

        Imagen 12. Campo Fecha Contable de la Ventana Retiros de Puntos de Venta

    #. En el campo "**Cuenta Bancaria**", podrá visualizar la cuenta caja asociada al socio del negocio vendedor en la configuración del terminal PDV.

        |Campo Cuenta Bancaria de la Ventana Retiros de Puntos de Venta|

        Imagen 13. Campo Cuenta Bancaria de la Ventana Retiros de Puntos de Venta

    #. En el campo "**Transferir Transacción de Caja a Banco**", podrá visualizar la cuenta a la cual serán transferidas todas las transacciones de la caja.

        |Campo Transferir Transacción de Caja a Banco de la Ventana Retiros de Puntos de Venta|

        Imagen 14. Campo Transferir Transacción de Caja a Banco de la Ventana Retiros de Puntos de Venta

    #. En el campo "**Tipo de Documento**", podrá visualizar el tipo de documento con el cual será generado el documento "**Pago**" en la ventana "**Caja**".

        |Campo Tipo de Documento de la Ventana Retiros de Puntos de Venta|

        Imagen 15. Campo Tipo de Documento de la Ventana Retiros de Puntos de Venta

    #. En el campo "**Tipo Contra-Documento**", podrá visualizar el tipo de contra documento a ser generado el documento "**Pago**" en la ventana "**Caja**".

        |Campo Tipo Contra Documento de la Ventana Retiros de Puntos de Venta|

        Imagen 16. Campo Tipo Contra-Documento de la Ventana Retiros de Puntos de Venta

    #. Seleccione en el campo "**Cargo**", el cargo que justifica el retiro de fondos del dinero de la caja. Para este caso, es utilizado como ejemplo el cargo "**Efectivo en Tránsito Administración Ventas**".

        |Campo Cargo de la Ventana Retiros de Puntos de Venta|

        Imagen 17. Campo Cargo de la Ventana Retiros de Puntos de Venta

    #. Seleccione en el campo "**Moneda**", la moneda correspondiente al retiro de fondos que se encuentra realizando desde el punto de venta.

        |Campo Moneda de la Ventana Retiros de Puntos de Venta|

        Imagen 18. Campo Moneda de la Ventana Retiros de Puntos de Venta

#. Seleccione la opción "**OK**", para reflejar en ADempiere el retiro de fondos del punto de venta y generar en la ventana "**Caja**" los documentos que avalan dicha transacción.

    |Opción OK de la Ventana Retiros de Puntos de Venta|

    Imagen 19. Opción OK de la Ventana Retiros de Puntos de Venta

.. note::

    Por cada retiro de fondo realizado desde el punto de venta, ADempiere crea en la ventana "**Caja**" los siguientes documentos:
    
        - Un documento de pago asociando en el campo "**Cuenta**", la caja seleccionada en el campo "**Cuenta Bancaria**" de la ventana "**Retiros de Puntos de Venta**".

        - De igual manera crea un documento de cobro asociando en el campo "**Cuenta**", la caja seleccionada en el campo "**Transferir transacción de caja a banco**", de la ventana "**Retiros de Puntos de Venta**".

**Consulta de Pago y Cobro Generados en Caja**
----------------------------------------------

#. Ubique los registros creados por el retiro de fondos en la ventana "**Caja**", con ayuda del número de documento ingresado en el campo "**No. del Documento**", de la ventana "**Retiros de Puntos de Venta**".

    |Número de Documento del Retiro de Fondos|

    Imagen 20. Número de Documento del Retiro de Fondos

#. Podrá visualizar en la parte inferior derecha de la ventana "**Caja**", el número de registros creados con el valor ingresado en el campo "**No. del Documento**", de la ventana "**Retiros de Puntos de Venta**".

    |Documento de Pago Generado en Caja|

    Imagen 20. Documento de Pago Generado en Caja

#. Podrá visualizar el registro de "**Pago**" creado desde la ventana "**Retiros de Puntos de Venta**".

    |Pago Creado desde la Ventana Retiros de Puntos de Venta|

    Imagen 21. Pago Creado desde la Ventana Retiros de Puntos de Venta

#. Seleccione el icono "**Próximo Registro**", ubicado en la barra de herramientas para visualizar el registro de "**Cobro**" creado desde la ventana "**Retiros de Puntos de Venta**".

    |Cobro Creado desde la Ventana Retiros de Puntos de Venta|

    Imagen 22. Cobro Creado desde la Ventana Retiros de Puntos de Venta

**Consultar Registro en Cierre de Caja**
----------------------------------------

#. Cada forma de pago y moneda por la que se realiza un retiro de fondos, se genera un documento de egreso y uno de ingreso en la ventana "**Caja**". Por cada documento generado se crea una línea con el mismo asociado, en la pestaña "**Línea de Cierre de Caja**", de la ventana "**Cierre de Caja**" correspondiente a los registros creados en estado "**Borrador** al realizar la apertura de caja. 

    #. Registro de "**Caja Administrativa**" en la ventana "**Cierre de Caja**".

        |Registro de Retiro Generado en Caja Administrativa|

        Imagen 23. Registro de Retiro Generado en Caja Administrativa

    #. Registro de "**Caja 04**" en la ventana "**Cierre de Caja**".

        |Registro de Retiro Generado en Caja 04|

        Imagen 24. Registro de Retiro Generado en Caja 04
