#' Fahrenheit conversion
#'
#' Convert degrees Fahrenheit temperatures to degrees Kelvin
#' @param F_temp The temperature in degrees Fahrenheit
#' @return The temperature in degrees Kelvin
#' @examples 
#' temp1 <- F_to_K(50);
#' temp2 <- F_to_K( c(50, 63, 23) );
#' @export
F_to_K <- function(F_temp){
  K_temp <- (F_temp - 32) * 5/9 + 273.15;
  return(K_temp);
}

#' Kelvin conversion
#'
#' Convert degrees Kelvin temperatures to degrees Fahrenheit
#' @param C_temp The temperature in degrees Kelvin
#' @return The temperature in degrees Fahrenheit
#' @examples 
#' temp1 <- K_to_F(22);
#' temp2 <- K_to_F( c(0, 12, 23) );
#' @export
K_to_F <- function(K_temp){
  F_temp <- (K_temp - 273.15) * 9/5 + 32;
  return(F_temp);
}