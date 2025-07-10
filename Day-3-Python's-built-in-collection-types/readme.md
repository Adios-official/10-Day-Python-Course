# ➡️ Day 3: Storing Collections of Data

Day 3 was all about organization! We learned how to store and manage multiple pieces of data using Python's powerful built-in collection types. This is the foundation for handling complex information.

* **Full Script:** [`day_3_script.py`](./day_3_script.py)
* **Cheat Sheet:** [`day_3_cheatsheet.md`](./day_3_cheatsheet.md)

---

### ⭐ Key Concepts Covered:

* **Lists:** Ordered, changeable collections for sequences of items.
* **Dictionaries:** Unordered collections of `key:value` pairs for connected data.
* **Tuples:** Ordered, **unchangeable** collections for protected data.
* **Sets:** Unordered collections of **unique** items.

---

### 💡 Highlight Snippet:

```python
# A dictionary to store a player's stats, including a list as a value
player_profile = {
    "name": "Alex",
    "level": 5,
    "inventory": ["sword", "shield", "potion"],
    "is_active": True
}

# Accessing data
print(f"Player: {player_profile['name']}")
print(f"First inventory item: {player_profile['inventory'][0]}")
