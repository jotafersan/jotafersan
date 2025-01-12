app.get('/products', (req, res) => {
    res.send([{ name: 'Arroz', price: 20 }]);
});
