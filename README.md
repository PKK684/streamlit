import streamlit as st

st.set_page_config(page_title="My Biodata", page_icon="🧑‍💻", layout="centered")

# ----- HEADER -----
st.title("My Biodata")

# ----- PERSONAL INFO -----
st.header("👤 Personal Information")
st.write("**Name:** K Prem")
st.write("**Email:** prem@gmail.com")
st.write("**Phone:** +91-9876543210")
st.write("**Location:** Chennai, India")

# ----- SUMMARY -----
st.header("📝 Summary")
st.write(
    "Enthusiastic and detail-oriented software developer with strong knowledge "
    "in Python, Java, and SQL. Interested in building scalable applications and "
    "exploring data science."
)

# ----- SKILLS -----
st.header("💡 Skills")
skills = ["Python", "Streamlit", "Java", "SQL", "Machine Learning"]
st.write(", ".join(skills))

# ----- EDUCATION -----
st.header("🎓 Education")
st.write("**BCA** - Peri college (2025)")


# ----- HOBBIES -----
st.header("🎯 Hobbies")
st.write("Reading tech blogs, coding challenges, playing chess")
