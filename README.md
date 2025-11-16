Control + Shift + m
requests==2.28.1
numpy==1.23.4
pandas==1.5.0
def test_add_numbers():
    assert add_numbers(2, 3) == 5
    assert add_numbers(-1, 1) == 0
    assert add_numbers(0, 0) == 0
