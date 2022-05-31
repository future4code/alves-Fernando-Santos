  let precoMenosDeUmaDuzia = 1.30
  let precoMaisDeUmaDuzia = 1.00
  
  if (quantidade >= 12) {
    return precoMaisDeUmaDuzia * quantidade
  } else if (quantidade < 12) {
    return precoMenosDeUmaDuzia * quantidade
  }
  
  }