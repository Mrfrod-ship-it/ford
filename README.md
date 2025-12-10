def greet(name="ໂລກ"):
    print(f"ສະບາຍດີ, {name}!")

def add(a, b):
    return a + b

def main():
    greet("ຜູ້ໃຊ້")
    print("2 + 3 =", add(2, 3))
    try:
        x = int(input("ໃສ່ຕົວເລກທຳອິດ: "))
        y = int(input("ໃສ່ຕົວເລກທີ່ສອງ: "))
        print(f"ຜົນບວກ: {add(x, y)}")
    except Exception as e:
        print("ມີຂໍ້ຜິດພາດ:", e)

if __name__ == "__main__":
    main()
