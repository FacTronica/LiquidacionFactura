# LiquidacionFactura
Documentación para realizar la Integración de Liquidación de Factura con Software Propio

3) Se agrega nueva sección: “COMISIONES Y OTROS CARGOS”, y campos que los agrupan en ENCABEZADO (“Valor Neto Comisiones y Otros Cargos”,
“Valor Comisiones y Otros Cargos No Afectos o Exentos” e “IVA Comisiones y Otros Cargos”. Esta área es obligatoria para Liquidaciones-Factura y opcional
para Facturas de Compra y Notas de Crédito/Débito que hacen referencia a Facturas de Compra.
4) Se admiten valores negativos en Liquidaciones Factura para los siguientes campos:
Del ENCABEZADO: “Monto Neto”, “Valor Neto Comisiones y Otros Cargos”, “Monto no afecto o exento”, “Valor Comisiones y Otros Cargos No Afectos o
Exentos”, “IVA”, “IVA Propio”, “IVA Terceros”, “IVA Comisiones y Otros Cargos”, “Monto Total”, “Monto Total en Otra Moneda”
Del DETALLE: “Valor por línea de Detalle” y “Valor por línea de detalle en Otra Moneda”.
De COMISIONES Y OTROS CARGOS: “Valor” y “Valor IVA Comisión u Otro Cargo”.
