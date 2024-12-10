 DECLARE
        counter INTEGER;
    BEGIN
        counter := 0;
        LOOP
            counter := counter + 1;
            IF (counter > 5) THEN
                BREAK;
            END IF;
            -- INSERT INTO dummy_data (ID) VALUES (:counter);
        END LOOP;
        RETURN counter;
    END; edit?
