ALGORITHM SentenceAnalysis

    SET length TO 0
    SET words TO 1
    SET vowels TO 0

    SET vowel_set TO {'a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U'}

    PRINT "Enter a sentence ending with a point ('.'): "

    WHILE TRUE DO
        READ character

        SET length TO length + 1

        IF character IN vowel_set THEN
            SET vowels TO vowels + 1
        END IF

        IF character == ' ' THEN
            SET words TO words + 1
        END IF

        IF character == '.' THEN
            BREAK
        END IF
    END WHILE

    PRINT "Length of the sentence: " + length
    PRINT "Number of words in the sentence: " + words
    PRINT "Number of vowels in the sentence: " + vowels

END ALGORITHM