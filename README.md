# DogModel

# https://dogmodel-iu6qufuohq-uc.a.run.app

# URL
  /predict
# Method
  POST

# Content-Type: application/x-www-form-urlencoded

# Key: gejala

# Value : [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0, 1, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]

# Response
# Jika sukses:
# {
    "Prediction": "Gastrointestinal Disease",
    "gejala": "Gejala yang dipilih: [28, 29, 39, 40, 43, 44]",
    "message": "Prediksi berhasil."
# }

# Jika Gejala dipilih kurang 3:
# {
    "message": "Gagal memprediksi penyakit karena gejala kurang dari 3."
# }
