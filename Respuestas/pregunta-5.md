db.productos.aggregate([
    {
        $group: {
            _id: "$categoria",
            stockTotal: { $sum: "$stock"}
        }
    }
])