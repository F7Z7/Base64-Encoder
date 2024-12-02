data_dict = {
    "000000": "A", "010000": "Q", "100000": "g", "110000": "w",
    "000001": "B", "010001": "R", "100001": "h", "110001": "x",
    "000010": "C", "010010": "S", "100010": "i", "110010": "y",
    "000011": "D", "010011": "T", "100011": "j", "110011": "z",
    "000100": "E", "010100": "U", "100100": "k", "110100": "0",
    "000101": "F", "010101": "V", "100101": "l", "110101": "1",
    "000110": "G", "010110": "W", "100110": "m", "110110": "2",
    "000111": "H", "010111": "X", "100111": "n", "110111": "3",
    "001000": "I", "011000": "Y", "101000": "o", "111000": "4",
    "001001": "J", "011001": "Z", "101001": "p", "111001": "5",
    "001010": "K", "011010": "a", "101010": "q", "111010": "6",
    "001011": "L", "011011": "b", "101011": "r", "111011": "7",
    "001100": "M", "011100": "c", "101100": "s", "111100": "8",
    "001101": "N", "011101": "d", "101101": "t", "111101": "9",
    "001110": "O", "011110": "e", "101110": "u", "111110": "+",
    "001111": "P", "011111": "f", "101111": "v", "111111": "/",
    "Padding": "="
}
data = input("Enter the string to be encoded: ")
asci_arr = []
bin_arr = []
for i in data:
    # print(ord(i))
    asci_arr.append(ord(i))
print(asci_arr)
print("asci")
for i in asci_arr:
    bin_arr.append(bin(i))
print(bin_arr)
print("binar")
bin_num = str("".join(map(str, bin_arr)))
print(bin_num)
print('binaryjoined')
new_bin=bin_num.replace("0b", "")
print(new_bin)
print("binary replaced")
l=len(new_bin)
print(l)
print("length")
if l % 8 != 0:
    new_bin += '0'
    l=l+1
print(new_bin)
print("binary corrected to 8")

# new_bin = (bin_num.replace("0b", ""))
# print(new_bin)
# print("binary without0b")
# binary_number = bin_num.ljust((len(bin_num) + 7) // 8 * 8, '0')
#
# # Split into groups of 8 bits
# octet = [bin_num[i:i+8] for i in range(0, len(bin_num), 8)]
# octet.remove('ob')

# print(octet)
