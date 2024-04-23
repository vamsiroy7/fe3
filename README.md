# fe3

 data_copy[col + '_log'] = np.log(data_copy[col] + 1)
        data_copy[col + '_reciprocal'] = 1 / (data_copy[col])
        data_copy[col + '_square_root'] = np.sqrt(data_copy[col])
        data_copy[col + '_exp'] = data_copy[col] ** 2


dummy_data = pd.DataFrame({
    'A': [1, np.nan, 3, 4, np.nan],
    'B': [np.nan, 2, 3, np.nan, 5],
    'C': [1, 2, 3, 4, 5]
})
