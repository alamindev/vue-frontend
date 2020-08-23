<template>
<div>
    <ReportNav />

    <div class="filter__content_main d-flex flex-md-row flex-column align-center align-md-stretch">
        <div class="filter__content_left d-flex">
            <div class="content_image">
                <v-img height="250" src="https://cdn.venzeo.com/eu/org/demo/img/reports/orig/blocked.jpg?Signature=MYrJwrKMAzT67~92rJj078r0f-Cg6lNZMguLP7DXEmIlEUyJ6qck-FQXk1wehHc5CX-UDA1hndPObEaN-UB-3oCnPGBePNGtdjB0ImNhYfnGuaAH5MViJw7dsMF7nANG7PMllXchycpj8wmqCPjAzs9~F1ixjzChx2IXk6VKzCF99bgXpfQSwKpycYV-fyf0iTmao4WneXargNgu7dVY0PEQGi5co~pFvjXgRq4iv2VsvPagzZi6oYEFqKV2HVklNa0ZBjD-X5hnoFecXlEQXjRVPZhEeW-SclEHpWibeJlK7FthPj4rCR2kzAxNxJvsxAF2g3PhpCLlqV8fA0CFcg__&Expires=2145916800&Key-Pair-Id=APKAJ4XWZYGFCJWQZ2ZQ&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9jZG4udmVuemVvLmNvbS9ldS9vcmcvZGVtby9pbWcvcmVwb3J0cy8qL2Jsb2NrZWQuanBnKiIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MjE0NTkxNjgwMH19fV19"></v-img>
                <div class="photo__view">
                    <v-icon>photo</v-icon> 1+ Photo
                </div>
            </div>
            <div class="map_image">
                <v-img height="250" src="/map.png"></v-img>
            </div>
        </div>
        <div class="filter__content_right">
            <div class="content_left">
                <ul>
                    <li>
                        <v-icon>edit_location</v-icon> Svážná 644/6, 140 00 Praha 4-Nusle, Czechia (50.059095, 14.443390 | ±20m)
                    </li>
                    <li>
                        <v-icon>more</v-icon> Blocked container
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> Unchecked (20. Aug 2020 02:49)
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> 20. Aug 2020 02:49 (3 days ago)
                    </li>
                    <li>
                        <v-icon>person_search</v-icon> John Demo
                    </li>
                    <li>
                        <v-icon>directions_car</v-icon> Blocking car
                    </li>
                </ul>
                <div class="button__area">
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>remove_red_eye </v-icon> See details
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>location_on </v-icon> Show map
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>mail_outline </v-icon> Send via Mail
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>chat_bubble_outline </v-icon> Comments
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>accessibility_new </v-icon> Street view
                    </v-btn>
                </div>
            </div>
            <div class="content_right">
                <div class="mb-2 d-flex flex-no-wrap align-center">
                    id: <span class="content__id ml-1">4444</span>

                </div>
                <div class="edit__icon">
                    <v-icon>edit </v-icon>
                </div>
            </div>
        </div>
    </div>
    <div class="filter__content_main d-flex flex-md-row flex-column align-center align-md-stretch">
        <div class="filter__content_left d-flex">
            <div class="content_image">
                <v-img height="250" src="https://cdn.venzeo.com/eu/org/demo/img/reports/orig/blocked.jpg?Signature=MYrJwrKMAzT67~92rJj078r0f-Cg6lNZMguLP7DXEmIlEUyJ6qck-FQXk1wehHc5CX-UDA1hndPObEaN-UB-3oCnPGBePNGtdjB0ImNhYfnGuaAH5MViJw7dsMF7nANG7PMllXchycpj8wmqCPjAzs9~F1ixjzChx2IXk6VKzCF99bgXpfQSwKpycYV-fyf0iTmao4WneXargNgu7dVY0PEQGi5co~pFvjXgRq4iv2VsvPagzZi6oYEFqKV2HVklNa0ZBjD-X5hnoFecXlEQXjRVPZhEeW-SclEHpWibeJlK7FthPj4rCR2kzAxNxJvsxAF2g3PhpCLlqV8fA0CFcg__&Expires=2145916800&Key-Pair-Id=APKAJ4XWZYGFCJWQZ2ZQ&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9jZG4udmVuemVvLmNvbS9ldS9vcmcvZGVtby9pbWcvcmVwb3J0cy8qL2Jsb2NrZWQuanBnKiIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MjE0NTkxNjgwMH19fV19"></v-img>
                <div class="photo__view">
                    <v-icon>photo</v-icon> 1+ Photo
                </div>
            </div>
            <div class="map_image">
                <v-img height="250" src="/map.png"></v-img>
            </div>
        </div>
        <div class="filter__content_right">
            <div class="content_left">
                <ul>
                    <li>
                        <v-icon>edit_location</v-icon> Svážná 644/6, 140 00 Praha 4-Nusle, Czechia (50.059095, 14.443390 | ±20m)
                    </li>
                    <li>
                        <v-icon>more</v-icon> Blocked container
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> Unchecked (20. Aug 2020 02:49)
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> 20. Aug 2020 02:49 (3 days ago)
                    </li>
                    <li>
                        <v-icon>person_search</v-icon> John Demo
                    </li>
                    <li>
                        <v-icon>directions_car</v-icon> Blocking car
                    </li>
                </ul>
                <div class="button__area">
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>remove_red_eye </v-icon> See details
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>location_on </v-icon> Show map
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>mail_outline </v-icon> Send via Mail
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>chat_bubble_outline </v-icon> Comments
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>accessibility_new </v-icon> Street view
                    </v-btn>
                </div>
            </div>
            <div class="content_right">
                <div class="mb-2 d-flex flex-no-wrap align-center">
                    id: <span class="content__id ml-1">4444</span>

                </div>
                <div class="edit__icon">
                    <v-icon>edit </v-icon>
                </div>
            </div>
        </div>
    </div>
    <div class="filter__content_main d-flex flex-md-row flex-column align-center align-md-stretch">
        <div class="filter__content_left d-flex">
            <div class="content_image">
                <v-img height="250" src="https://cdn.venzeo.com/eu/org/demo/img/reports/orig/blocked.jpg?Signature=MYrJwrKMAzT67~92rJj078r0f-Cg6lNZMguLP7DXEmIlEUyJ6qck-FQXk1wehHc5CX-UDA1hndPObEaN-UB-3oCnPGBePNGtdjB0ImNhYfnGuaAH5MViJw7dsMF7nANG7PMllXchycpj8wmqCPjAzs9~F1ixjzChx2IXk6VKzCF99bgXpfQSwKpycYV-fyf0iTmao4WneXargNgu7dVY0PEQGi5co~pFvjXgRq4iv2VsvPagzZi6oYEFqKV2HVklNa0ZBjD-X5hnoFecXlEQXjRVPZhEeW-SclEHpWibeJlK7FthPj4rCR2kzAxNxJvsxAF2g3PhpCLlqV8fA0CFcg__&Expires=2145916800&Key-Pair-Id=APKAJ4XWZYGFCJWQZ2ZQ&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9jZG4udmVuemVvLmNvbS9ldS9vcmcvZGVtby9pbWcvcmVwb3J0cy8qL2Jsb2NrZWQuanBnKiIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MjE0NTkxNjgwMH19fV19"></v-img>
                <div class="photo__view">
                    <v-icon>photo</v-icon> 1+ Photo
                </div>
            </div>
            <div class="map_image">
                <v-img height="250" src="/map.png"></v-img>
            </div>
        </div>
        <div class="filter__content_right">
            <div class="content_left">
                <ul>
                    <li>
                        <v-icon>edit_location</v-icon> Svážná 644/6, 140 00 Praha 4-Nusle, Czechia (50.059095, 14.443390 | ±20m)
                    </li>
                    <li>
                        <v-icon>more</v-icon> Blocked container
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> Unchecked (20. Aug 2020 02:49)
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> 20. Aug 2020 02:49 (3 days ago)
                    </li>
                    <li>
                        <v-icon>person_search</v-icon> John Demo
                    </li>
                    <li>
                        <v-icon>directions_car</v-icon> Blocking car
                    </li>
                </ul>
                <div class="button__area">
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>remove_red_eye </v-icon> See details
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>location_on </v-icon> Show map
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>mail_outline </v-icon> Send via Mail
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>chat_bubble_outline </v-icon> Comments
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>accessibility_new </v-icon> Street view
                    </v-btn>
                </div>
            </div>
            <div class="content_right">
                <div class="mb-2 d-flex flex-no-wrap align-center">
                    id: <span class="content__id ml-1">4444</span>

                </div>
                <div class="edit__icon">
                    <v-icon>edit </v-icon>
                </div>
            </div>
        </div>
    </div>
    <div class="filter__content_main d-flex flex-md-row flex-column align-center align-md-stretch">
        <div class="filter__content_left d-flex">
            <div class="content_image">
                <v-img height="250" src="https://cdn.venzeo.com/eu/org/demo/img/reports/orig/blocked.jpg?Signature=MYrJwrKMAzT67~92rJj078r0f-Cg6lNZMguLP7DXEmIlEUyJ6qck-FQXk1wehHc5CX-UDA1hndPObEaN-UB-3oCnPGBePNGtdjB0ImNhYfnGuaAH5MViJw7dsMF7nANG7PMllXchycpj8wmqCPjAzs9~F1ixjzChx2IXk6VKzCF99bgXpfQSwKpycYV-fyf0iTmao4WneXargNgu7dVY0PEQGi5co~pFvjXgRq4iv2VsvPagzZi6oYEFqKV2HVklNa0ZBjD-X5hnoFecXlEQXjRVPZhEeW-SclEHpWibeJlK7FthPj4rCR2kzAxNxJvsxAF2g3PhpCLlqV8fA0CFcg__&Expires=2145916800&Key-Pair-Id=APKAJ4XWZYGFCJWQZ2ZQ&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9jZG4udmVuemVvLmNvbS9ldS9vcmcvZGVtby9pbWcvcmVwb3J0cy8qL2Jsb2NrZWQuanBnKiIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MjE0NTkxNjgwMH19fV19"></v-img>
                <div class="photo__view">
                    <v-icon>photo</v-icon> 1+ Photo
                </div>
            </div>
            <div class="map_image">
                <v-img height="250" src="/map.png"></v-img>
            </div>
        </div>
        <div class="filter__content_right">
            <div class="content_left">
                <ul>
                    <li>
                        <v-icon>edit_location</v-icon> Svážná 644/6, 140 00 Praha 4-Nusle, Czechia (50.059095, 14.443390 | ±20m)
                    </li>
                    <li>
                        <v-icon>more</v-icon> Blocked container
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> Unchecked (20. Aug 2020 02:49)
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> 20. Aug 2020 02:49 (3 days ago)
                    </li>
                    <li>
                        <v-icon>person_search</v-icon> John Demo
                    </li>
                    <li>
                        <v-icon>directions_car</v-icon> Blocking car
                    </li>
                </ul>
                <div class="button__area">
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>remove_red_eye </v-icon> See details
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>location_on </v-icon> Show map
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>mail_outline </v-icon> Send via Mail
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>chat_bubble_outline </v-icon> Comments
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>accessibility_new </v-icon> Street view
                    </v-btn>
                </div>
            </div>
            <div class="content_right">
                <div class="mb-2 d-flex flex-no-wrap align-center">
                    id: <span class="content__id ml-1">4444</span>

                </div>
                <div class="edit__icon">
                    <v-icon>edit </v-icon>
                </div>
            </div>
        </div>
    </div>
    <div class="filter__content_main d-flex flex-md-row flex-column align-center align-md-stretch">
        <div class="filter__content_left d-flex">
            <div class="content_image">
                <v-img height="250" src="https://cdn.venzeo.com/eu/org/demo/img/reports/orig/blocked.jpg?Signature=MYrJwrKMAzT67~92rJj078r0f-Cg6lNZMguLP7DXEmIlEUyJ6qck-FQXk1wehHc5CX-UDA1hndPObEaN-UB-3oCnPGBePNGtdjB0ImNhYfnGuaAH5MViJw7dsMF7nANG7PMllXchycpj8wmqCPjAzs9~F1ixjzChx2IXk6VKzCF99bgXpfQSwKpycYV-fyf0iTmao4WneXargNgu7dVY0PEQGi5co~pFvjXgRq4iv2VsvPagzZi6oYEFqKV2HVklNa0ZBjD-X5hnoFecXlEQXjRVPZhEeW-SclEHpWibeJlK7FthPj4rCR2kzAxNxJvsxAF2g3PhpCLlqV8fA0CFcg__&Expires=2145916800&Key-Pair-Id=APKAJ4XWZYGFCJWQZ2ZQ&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9jZG4udmVuemVvLmNvbS9ldS9vcmcvZGVtby9pbWcvcmVwb3J0cy8qL2Jsb2NrZWQuanBnKiIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MjE0NTkxNjgwMH19fV19"></v-img>
                <div class="photo__view">
                    <v-icon>photo</v-icon> 1+ Photo
                </div>
            </div>
            <div class="map_image">
                <v-img height="250" src="/map.png"></v-img>
            </div>
        </div>
        <div class="filter__content_right">
            <div class="content_left">
                <ul>
                    <li>
                        <v-icon>edit_location</v-icon> Svážná 644/6, 140 00 Praha 4-Nusle, Czechia (50.059095, 14.443390 | ±20m)
                    </li>
                    <li>
                        <v-icon>more</v-icon> Blocked container
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> Unchecked (20. Aug 2020 02:49)
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> 20. Aug 2020 02:49 (3 days ago)
                    </li>
                    <li>
                        <v-icon>person_search</v-icon> John Demo
                    </li>
                    <li>
                        <v-icon>directions_car</v-icon> Blocking car
                    </li>
                </ul>
                <div class="button__area">
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>remove_red_eye </v-icon> See details
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>location_on </v-icon> Show map
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>mail_outline </v-icon> Send via Mail
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>chat_bubble_outline </v-icon> Comments
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>accessibility_new </v-icon> Street view
                    </v-btn>
                </div>
            </div>
            <div class="content_right">
                <div class="mb-2 d-flex flex-no-wrap align-center">
                    id: <span class="content__id ml-1">4444</span>

                </div>
                <div class="edit__icon">
                    <v-icon>edit </v-icon>
                </div>
            </div>
        </div>
    </div>
    <div class="filter__content_main d-flex flex-md-row flex-column align-center align-md-stretch">
        <div class="filter__content_left d-flex">
            <div class="content_image">
                <v-img height="250" src="https://cdn.venzeo.com/eu/org/demo/img/reports/orig/blocked.jpg?Signature=MYrJwrKMAzT67~92rJj078r0f-Cg6lNZMguLP7DXEmIlEUyJ6qck-FQXk1wehHc5CX-UDA1hndPObEaN-UB-3oCnPGBePNGtdjB0ImNhYfnGuaAH5MViJw7dsMF7nANG7PMllXchycpj8wmqCPjAzs9~F1ixjzChx2IXk6VKzCF99bgXpfQSwKpycYV-fyf0iTmao4WneXargNgu7dVY0PEQGi5co~pFvjXgRq4iv2VsvPagzZi6oYEFqKV2HVklNa0ZBjD-X5hnoFecXlEQXjRVPZhEeW-SclEHpWibeJlK7FthPj4rCR2kzAxNxJvsxAF2g3PhpCLlqV8fA0CFcg__&Expires=2145916800&Key-Pair-Id=APKAJ4XWZYGFCJWQZ2ZQ&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9jZG4udmVuemVvLmNvbS9ldS9vcmcvZGVtby9pbWcvcmVwb3J0cy8qL2Jsb2NrZWQuanBnKiIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MjE0NTkxNjgwMH19fV19"></v-img>
                <div class="photo__view">
                    <v-icon>photo</v-icon> 1+ Photo
                </div>
            </div>
            <div class="map_image">
                <v-img height="250" src="/map.png"></v-img>
            </div>
        </div>
        <div class="filter__content_right">
            <div class="content_left">
                <ul>
                    <li>
                        <v-icon>edit_location</v-icon> Svážná 644/6, 140 00 Praha 4-Nusle, Czechia (50.059095, 14.443390 | ±20m)
                    </li>
                    <li>
                        <v-icon>more</v-icon> Blocked container
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> Unchecked (20. Aug 2020 02:49)
                    </li>
                    <li>
                        <v-icon>av_timer</v-icon> 20. Aug 2020 02:49 (3 days ago)
                    </li>
                    <li>
                        <v-icon>person_search</v-icon> John Demo
                    </li>
                    <li>
                        <v-icon>directions_car</v-icon> Blocking car
                    </li>
                </ul>
                <div class="button__area">
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>remove_red_eye </v-icon> See details
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>location_on </v-icon> Show map
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>mail_outline </v-icon> Send via Mail
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>chat_bubble_outline </v-icon> Comments
                    </v-btn>
                    <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                        <v-icon>accessibility_new </v-icon> Street view
                    </v-btn>
                </div>
            </div>
            <div class="content_right">
                <div class="mb-2 d-flex flex-no-wrap align-center">
                    id: <span class="content__id ml-1">4444</span>

                </div>
                <div class="edit__icon">
                    <v-icon>edit </v-icon>
                </div>
            </div>
        </div>
    </div>

</div>
</template>

<script>
import ReportNav from '~/components/ReportNav.vue'

export default {
    components: {
        ReportNav,
    }
}
</script>

<style lang="scss">
.filter__content_main {
    border-bottom: 1px solid #aaaaaa;
}

.content_left {
    padding-left: 10px;
    padding-top: 10px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;

    ul {
        list-style: none;
        padding: 0;
        color: #808080 !important;
        padding-bottom: 2px;
        font-size: 15px;

        li {
            .v-icon {
                font-size: 18px
            }

            font-size: 14px;

            .theme--light.v-icon {
                color: #acacac;
            }
        }
    }
}

.content_image {
    width: 240px;

}

.map_image {
    width: 240px;
}

.button__area {
    display: flex;
    flex-wrap: wrap;
}

.content__id {
    background: #aaa;
    border-radius: 50px;
    padding: 5px 10px;
    color: white;
}

.filter__content_main:hover .filter__content_right {
    background: #ebebeb;
}

.edit__icon {
    background: #aaa;
    border-radius: 50px;
    padding: 5px 10px;
    display: inline-block;

    .v-icon {
        color: white;
        font-size: 18px;
    }
}

.content_right {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    padding: 15px;
}

.filter__content_right {
    width: 100%;
    display: flex;
    justify-content: space-between;
}

.button__area button {
    background: white;
    border: 1px solid #ccc;

    &:hover {
        color: #333;
        background-color: #ebebeb;
        border-color: #adadad;
    }
}

.content_image {
    position: relative;

    .photo__view {
        position: absolute;
        width: 100%;
        height: 42px;
        background: #102c42;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        bottom: 0;
        font-size: 14px;

        .v-icon {
            color: white;
            font-size: 26px;
            margin-right: 5px;
        }
    }
}
</style>
