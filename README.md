Urbanisation/population weighted density data for UK and Australian constituencies. Done using GHSL 2025 data for UK constituencies and census 2021 for Australia.

Informal description: For each person we take a symmetric Gaussian kernal with E[R^2]=(5km)^2, that is, we are calculating population density over a blob centred
on you where the "typical" point in the bloc is 5km away. We then take a geometric mean of this density for all people in each constituency.
