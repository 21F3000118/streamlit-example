import streamlit as st

def largest_number(a, b, c):
    return max(a, b, c)

def main():
    st.title("Find the Largest Number")
    
    st.write("Enter three numbers:")
    a = st.number_input("Enter the first number:", value=0)
    b = st.number_input("Enter the second number:", value=0)
    c = st.number_input("Enter the third number:", value=0)
    
    result = largest_number(a, b, c)
    st.write(f"The largest number among {a}, {b}, and {c} is: {result}")

if __name__ == "__main__":
    main()
