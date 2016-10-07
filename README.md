# temperature-converter
A ruby project to convert centigrade into fahrenheit

#celsius * 1.8 + 32 = F

puts "Enter degrees in celsius"
celsius = gets.to_f

def convert(n)
  return n * 1.8 + 32
end

val = convert(celsius)
puts "The temperature is #{val} degrees Fahrenheit"
