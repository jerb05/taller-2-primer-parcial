db.productos.updateOne(
    { nombre: "Laptop Pro" },
    { $set: { stock: 25 } }
)